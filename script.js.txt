function changebg(){
    let r= Math.random()*255;
    let g= Math.random()*255;
    let b= Math.random()*255;
    // random generates value b/w 0 to 0.99 not one also multiplication is done with 255 to get the walue range fron 0 to less than 255
    let body_bg= document.querySelector('body');
    body_bg.style.cssText=`background-color: rgb(${r},${g},${b})`;
    //here we have used the back tick not single quotes
}



let mode= document.querySelector('#mode');
let body= document.querySelector('body');
let premode='light';
mode.addEventListener('click',()=>{
    if(pemode==='light'){
        premode==='dark';
        body.classList.remove('dark');
        body.classList.remove('light');

    }else{
        pemode===('light')
        body.classList.remove('light');
        body.classList.remove('dark');

    }
    console.log(premode);
});