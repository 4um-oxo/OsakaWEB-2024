<template>
    <div class="w-100">
        
        <div class="logo ms-3">
            <svg class="mt-5 animate__animated animate__bounceIn" xmlns="http://www.w3.org/2000/svg" width="230" height="226" viewBox="0 0 230 226" fill="none">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M229.942 139.447C229.04 169.89 220.045 203.562 194.23 219.775C170.538 234.656 141.728 214.247 113.802 212.391C89.448 210.771 63.9522 222.92 43.4146 209.747C19.3138 194.289 -1.45055 168.013 0.0795441 139.447C1.57742 111.482 31.5863 96.9036 50.5631 76.2866C71.0823 53.9938 83.8129 20.3488 113.802 15.8949C145.871 11.1321 176.943 30.6137 199.134 54.2214C220.652 77.1124 230.871 108.062 229.942 139.447Z" fill="#FF8D3B"/>
                <circle cx="142.882" cy="18.5" r="18.5" fill="white"/>
                <rect x="61" y="79" width="130" height="88" rx="26" fill="white"/>
                <circle cx="96.8822" cy="18.5" r="18.5" fill="white"/>
                <ellipse cx="144.882" cy="16" rx="11.5" ry="11" fill="black"/>
                <ellipse cx="98.8822" cy="16" rx="11.5" ry="11" fill="black"/>
                <path d="M119.509 120.211C119.509 126.169 114.694 131 108.755 131C102.815 131 98 126.169 98 120.211C98 114.252 102.815 109.421 108.755 109.421C114.694 109.421 119.509 114.252 119.509 120.211Z" fill="#EDEDED"/>
                <path d="M127.038 109.421C127.038 115.38 122.223 120.211 116.283 120.211C110.343 120.211 105.528 115.38 105.528 109.421C105.528 103.462 110.343 98.6317 116.283 98.6317C122.223 98.6317 127.038 103.462 127.038 109.421Z" fill="#EDEDED"/>
                <path d="M139.943 119.132C139.943 125.09 135.128 129.921 129.189 129.921C123.249 129.921 118.434 125.09 118.434 119.132C118.434 113.173 123.249 108.342 129.189 108.342C135.128 108.342 139.943 113.173 139.943 119.132Z" fill="#EDEDED"/>
                <path d="M137.792 100.789C137.792 106.748 132.977 111.579 127.038 111.579C121.098 111.579 116.283 106.748 116.283 100.789C116.283 94.8306 121.098 90 127.038 90C132.977 90 137.792 94.8306 137.792 100.789Z" fill="#EDEDED"/>
                <path d="M147.472 109.421C147.472 115.38 142.657 120.211 136.717 120.211C130.777 120.211 125.962 115.38 125.962 109.421C125.962 103.462 130.777 98.6317 136.717 98.6317C142.657 98.6317 147.472 103.462 147.472 109.421Z" fill="#EDEDED"/>
                <path d="M155 119.132C155 125.09 150.185 129.921 144.245 129.921C138.306 129.921 133.491 125.09 133.491 119.132C133.491 113.173 138.306 108.342 144.245 108.342C150.185 108.342 155 113.173 155 119.132Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M149.772 109.876C147.849 108.72 147.663 108.48 147.02 106.325L131.19 118.677C133.113 119.833 133.3 120.073 133.943 122.227L149.772 109.876Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M142.718 108.451C139.002 108.986 136.814 106.655 137.572 102.965L128.565 111.469C132.282 110.935 134.469 113.266 133.712 116.955L142.718 108.451Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M139.346 109.527C137.006 110.728 136.428 110.728 134.088 109.527V128.736C136.428 127.535 137.006 127.535 139.346 128.736V109.527Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M137.953 110.381C133.09 113.901 128.274 112.228 126.621 106.446L122.575 118.171C127.438 114.652 132.254 116.325 133.908 122.107L137.953 110.381Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M135.263 113.198C130.338 120.701 122.731 120.932 117.362 113.742L117.737 126.144C122.661 118.642 130.269 118.41 135.638 125.6L135.263 113.198Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M140.228 99.2224C138.011 98.4543 137.742 98.2146 136.722 96.0959L123.527 110.988C125.744 111.756 126.013 111.995 127.033 114.114L140.228 99.2224Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M126.414 106.325C125.771 108.48 125.585 108.72 123.662 109.876L139.491 122.227C140.134 120.073 140.321 119.833 142.244 118.677L126.414 106.325Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M129.273 101.634C127.272 103.56 125.728 103.56 123.727 101.634V117.209C125.728 115.283 127.272 115.283 129.273 117.209V101.634Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M126.285 106.8C124.783 112.814 119.88 114.706 114.747 111.251L119.187 122.832C120.689 116.817 125.592 114.926 130.724 118.38L126.285 106.8Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M119.123 108.094C121.085 110.234 121.213 111.331 119.8 113.869L137.104 111.827C135.142 109.687 135.013 108.59 136.427 106.052L119.123 108.094Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M117.46 95.8824C116.34 98.0828 115.999 98.3561 113.613 98.9694L125.861 114.328C126.981 112.128 127.322 111.855 129.707 111.241L117.46 95.8824Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M116.5 102.947C117.403 107.385 114.768 110.184 110.3 109.533L119.292 118.053C118.389 113.615 121.024 110.816 125.492 111.467L116.5 102.947Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M130.542 108.428C127.817 108.081 127.241 107.648 126.146 105.12L114.929 120.125C117.655 120.472 118.23 120.904 119.325 123.432L130.542 108.428Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M121.328 111.768C119.44 113.797 117.892 113.879 115.801 112.06L116.615 127.574C118.504 125.545 120.052 125.464 122.142 127.282L121.328 111.768Z" fill="#EDEDED"/>
                <path fill-rule="evenodd" clip-rule="evenodd" d="M105.765 107.169C105.27 109.495 105.055 109.804 103.045 111.067L119.273 122.462C119.768 120.136 119.983 119.827 121.992 118.564L105.765 107.169Z" fill="#EDEDED"/>
                <path d="M156 121H97C97 133.233 105.453 143.611 117.177 147.273V151.399C117.177 152.279 117.945 153 118.883 153H133.947C134.886 153 135.654 152.279 135.654 151.399V147.325C147.464 143.708 156 133.29 156 121Z" fill="#FFC700"/>
              </svg>
        </div>


        <div class="explain border border-2 border- rounded mt-4 p-3">
            <h2 class="">使い方</h2>
            <p class="">
                地方又は県を選んでもらいNEXTをクリックし進む
                地方ごとの人気料理が元々入っており、自分で追加するかそのまま進むか選んでもらいます。選び終えたらSTARTをクリックし、ルーレット結果を待ってもらいます。その後SHARE画面に進んでもらい何の料理になったか確認してもらいます。
            </p>
        </div>

        <div class="modalBtn">
            <a href="/team 3/rouletteStart.html" class="text-white  text-decoration-none">Next</a>
        </div>

        
    </div>
</template>

<script>
    export default {
        name : "Explanation"
    }

    $(function() {
    var spinning = false;
    var currentPosition = 0;
    var options = $(".roulette .options div");
    var interval;
  
    function startRoulette() {
        if (!spinning) {
            spinning = true;
            interval = setInterval(function() {
                currentPosition++;
                if (currentPosition >= options.length) {
                    currentPosition = 0;
                }
                options.removeClass("selected");
                options.eq(currentPosition).addClass("selected");
            }, 100);
        }
    }
  
    function stopRoulette() {
        clearInterval(interval);
        spinning = false;
    }
  
    $(".start").click(startRoulette);
    $(".stop").click(stopRoulette);
});


    $(function () {
    var modalBtn = $(".modalBtn");
    var modalBtnCloseFix = $(".modalBtnClose");
    var modalBg = $(".modalBg");
    var modalMain = $(".modalMain");
    modalBtn.on("click", function (e) {
        $(this).next(modalBg).fadeIn();
        $(this).next(modalBg).next(modalMain).removeClass("_slideDown");
        $(this).next(modalBg).next(modalMain).addClass("_slideUp");
    });

    //
    //鼻の部分をクリックしたら閉じる
    //
    $(".addBtn").on("click", () => {
        $("#inputForm").toggle(); 
        $(".addBtn").css("display", "none")
        // var newElement = $("<p>New Element</p>");
        // $(".addBox").append(newElement);
    })

    $("#submit").on("click", () => {
        preventDefault();
        var inputData = $("#inputForm").val();
        var newElement = $(`<p>${inputData}</p>`);
        $(".addBox").append(newElement)
    })

    modalBtnCloseFix.on("click", function (e) {
        modalBg.fadeOut();
        modalMain.removeClass("_slideUp");
        modalMain.addClass("_slideDown");
    });

    //
    //モーダルの外をクリックしたら閉じるを支えている部分
    //modalMainをクリックしても閉じないようにする
    //

    modalMain.on("click", function (e) {
        e.stopPropagation();
    });

    //
    //モーダルの外をクリックしたら閉じる
    //

    // modalBg.on("click", function () {
    //     $(this).fadeOut();
    //     $(this).next(modalMain).removeClass("_slideUp");
    //     $(this).next(modalMain).addClass("_slideDown");
    // });
});

</script>

<style>

html {
    height: 100vh;
}


.roulette {
    width: 200px;
    height: 200px;
    border: 2px solid #000;
    border-radius: 50%;
    position: relative;
    overflow: hidden;
}

.options {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.options div {
    margin-bottom: 10px;
    font-size: 18px;
    font-weight: bold;
    transition: all 0.2s ease;
}

.selected {
    color: red;
}


/*
Next btn set
*/
.modalBtn {
    width: 150px;
    height: 35px;
    margin: 30px auto 0;
    color: #fff;
    font-size: 1.4rem;
    font-weight: bold;
    line-height: 35px;
    text-align: center;
    cursor: pointer;
    border-radius: 25px;
    background: #ffc700;
}

/*モーダル用*/
.modalBg {
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.6);
    position: fixed;
    top: 0;
    left: 0;
    z-index: 10;
    display: none;
}

/*
モーダル幅
*/

.modalMain {
    width: 100%;
    height: 90vh;
    position: fixed;
    bottom: -680px;
    left: 0;
    z-index: 11;
    opacity: 0;
    padding: 50px 0 0 30px;
    background: #ff8d3b;
    border-radius: 20px 20px 0 0;

    h1 {
        font-size: 2rem;
        color: #fff;
    }

    /*
戻るボタン　顔の部分
*/

    .modalBtnClose {
        position: absolute;
        top: -35px;
        left: 180px;

        svg {
            width: 70px;
            height: 70px;
        }
    }

    .leftEye {
        position: absolute;
        top: -55px;
        left: 90px;

        svg {
            width: 80px;
            height: 80px;
        }
    }

    .rightEye {
        position: absolute;
        top: -55px;
        left: 260px;

        svg {
            width: 80px;
            height: 80px;
        }
    }

    /*追加ボックス*/
    .addBox {
        margin: 40px 0;
        display: flex;
        flex-wrap: wrap;
        justify-content: flex-start;
        align-items: center;

        .addStyle {
            width: 120px;
            height: 25px;
            margin: 10px 10px 0 0;
            font-size: 1.2rem;
            text-align: center;
            line-height: 25px;
            border-radius: 25px;
            background-color: #fff;
        }

        .addBtn a {
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            width: 50px;
            height: 25px;
            margin: 10px 20px 0 0;
            color: #000;
            text-decoration: none;
            font-size: 1rem;
            text-align: center;
            line-height: 25px;
            border-radius: 15px;
            background-color: #fff;
        }
    }

    /*ルーレットボックス*/
    .rouletteBox {
        display: block;
        width: 300px;
        height: 300px;
        margin: 50px 30px;
        border-radius: 50%;
        background-color: #fff;
    }

    .btnStyle a {
        display: block;
        width: 200px;
        height: 35px;
        margin: 0 80px;
        font-size: 1.2rem;
        font-weight: bold;
        text-align: center;
        line-height: 35px;
        text-decoration: none;
        color: #ff8d3b;
        border-radius: 35px;
        background-color: #fff;
    }
}

/*モーダル開く下から上*/

@keyframes SlideUp {
    0% {
        opacity: 0;
        transform: translateY(-1%);
    }
    100% {
        opacity: 1;
        transform: translateY(-80%);
    }
}

/*モーダル閉じる上から下*/

@keyframes SlideDown {
    0% {
        opacity: 1;
        transform: translateY(-80%);
    }
    100% {
        opacity: 0;
        transform: translateY(-1%);
    }
}

.modalMain._slideUp {
    animation: SlideUp 0.5s ease-in-out forwards;
}

.modalMain._slideDown {
    animation: SlideDown 0.5s ease-in-out forwards;
}


</style>