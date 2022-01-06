function upDate (previewPic){
    document.getElementById("image").style.backgroundImage = "url("+previewPic.src+")";
    document.getElementById("image").innerHTML=previewPic.alt; 
    document.getElementById("image").style.backgroundColor = "#cceecc";
}
function unDo(){
    document.getElementById("image").style.backgroundImage = "url('')";
    document.getElementById("image").innerHTML="Hover over an image below to display here."; 
    document.getElementById("image").style.backgroundColor = "#8e68ff";
}