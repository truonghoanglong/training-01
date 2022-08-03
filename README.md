# listen event scroll

document.addEventListener("DOMContentLoaded",function(){
    //bat su kien lan chuot
    var status = false;

    // document.que  đôi tượng muôn add vào

    var clasCss = document.querySelector('')
    window.addEventListener('scroll',function(){
        console.log(window.pageYOffset)
        if(window.pageYOffset > 300){
            if(status == false){
                console.log("tren 300")
                status = true


                doituongmuonac.classList.add('clasCss')
            }
        }
    })
})
