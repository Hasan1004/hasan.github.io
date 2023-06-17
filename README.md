<!DOCTYPE html>
<html lang="en">
        <head>
           <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width,initial-scale=1.0">
     <title> free join now | private profile</title> 
            <link rel="icon" type="image/x-icon" href="/images.png" />


 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css" integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    
    
<style>

    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body{
        font-family: "Roboto", sans-serif;
        background:#f0f2f7
    }

    .container{
        position: absolute;
        top:50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    .label{
        padding: 10px;
        font-size: 18px;
        color: #111;
    }
    .copy-text{
        position: relative;
        padding: 10px;
        background: #fff;
        border-radius: 10px;
        display: flex;
    }

    .copy-text input.text{
        padding: 10px;
        font-size: 18px;
        border:none;
        outline: none;
        cursor: pointer;

    }

    .copy-text button{
        padding: 10px;
        background:#5784f5;
        color: #fff;
        font-size: 18px;
        border:none;
        outline: none;
        border-radius: 10px;
        cursor: pointer;


    }

    .copy-text button:active{
        background: #809ce2;
    }

    .copy-text button::before{
        content:"Copied";
        position: absolute;
        top: -50px;
        right: 0px;
        background-color: #5c81dc;
        padding: 8px 10px;
        border-radius: 20px;
        font-size: 15px;
        display: none;


    }

    .copy-text button:after{
        content: "";
        position: absolute;
        top:-20px;
        right: 25px;
        width: 10px;
        height: 10px;
        background:#5c81dc;
        transform: rotate(45deg);
        display: none;
    }

    .copy-text.active button::before,
    .copy-text.active button:after{
        display: block;
    }

</style>
<body>
    <div class="container">
        <div class="label">
          

        </div>
      <p>         Click on the copy button. You must copy the link and paste your Default browser Chrome, Safari, Firefox or Opera to Continue.
</p>
        <div class="copy-text">
            <input type="text" class="text" value="https://is.gd/P83HmD">
            <button>
                <i class="fa fa-clone"></i>
            </button>
        </div>
    </div>
<script>
    let copyText = document.querySelector(".copy-text");

    copyText.querySelector("button").addEventListener("click", function(){
        let input = copyText.querySelector("input.text");
        input.select();
        document.execCommand("copy");
        copyText.classList.add("active");
        window.getSelection().removeAllRanges();
        setTimeout(function(){
            copyText.classList.remove("active");
        }, 2500);
    });
</script>
</body>
</html>
