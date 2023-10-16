@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Sriracha:wght@400;700&display=swap');

    :root {
        --warna-bg: rgba(0, 0, 0, .4);
        --warna-teks: white;
        --warna-bingkai: rgba(255, 255, 255, .7);
        --bingkai: 10px;
        --gaya-font: 'Ubuntu', sans-serif;
        --gaya-font-sec: 'Sriracha', sans-serif;
    }

    body {
        background-color: #101010;
        font-family: var(--gaya-font);
        padding: 25px;
        -webkit-user-select: none;
        -ms-user-select: none;
        user-select: none;
    }

    a {
        text-decoration: none;
    }

    body::before {
        content: "\00A9  mardevgithub (damar wlean)";
        padding: 8px;
        border-radius: 12px;
        background: black;
        color: white;
        opacity: .7;
        font-size: 9px;
        position: fixed;
        bottom: 20px;
        left: 20px;
        z-index: 999
    }

    #bgbelakang {
        display: block;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: rgba(0, 0, 0, 0);
        -webkit-backdrop-filter: blur(2px);
        backdrop-filter: blur(2px);
        transition: all 1s ease;
    }

    #bgbelakang img {
        transition: all 1.7s ease;
        opacity: 0;
        width: 100%;
        height: 100%
    }

    #fotolove img {
        transition: all .5s ease;
        width: 75px;
        height: 75px;
        padding: 0;
        background: none
    }

    #loveIn img {
        display: inline-flex;
        background: none;
        width: 130px;
        height: 130px;
        transition: all .3s ease;
    }

    #ket,
    #kot,
    #ketgeser,
    .halo {
        text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);
        font-size: 17px;
        font-weight: 700;
        color: white
    }

    #ket,
    #kot {
        transform: scale(1) !important;
        margin-top: 20px !important;
        font-size: 16px;
        font-weight: 700;
        font-family: var(--gaya-font-sec);
        opacity: 1
    }

    #kot a {
        font-weight: 700;
        color: yellow
    }

    #ketgeser {
        position: absolute;
        margin-top: 30px;
        font-size: 10px;
        font-weight: 400;
        transform: scale(0);
        opacity: 0;
        transition: all .7s ease;
    }

    @keyframes leaves {
        0% {
            transform: scale(1.0);
        }

        100% {
            transform: scale(.85);
        }
    }

    .lovein {
        margin-top: 25vh;
        background: #fff;
        border-radius: 50%;
        width: 40px;
        height: 40px;
        padding: 10px;
        font-size: 30px;
        display: flex;
        align-items: center;
        text-align: center;
        justify-content: center;
        transition: all .3s ease;
    }

    .lovein:hover {
        cursor: pointer
    }

    .lovein svg {
        stroke: #ff0000;
        stroke-width: 1.3;
        fill: none;
        width: 35px;
        height: 35px
    }

    @keyframes kont {
        0% {
            left: -1px;
            top: -3px;
        }

        50% {
            left: 1px;
            top: 3px;
        }

        100% {
            left: -1px;
            top: -3px;
        }
    }

    blockquote {
        opacity: 0;
        visibility: hidden;
        transition: all 1s ease;
        position: relative;
        margin-left: 0;
        margin-right: 0;
    }

    blockquote {
        width: 400px;
        min-height: 30px;
        background: none;
        color: var(--warna-teks);
        text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);
        text-align: center;
        line-height: 1.3em;
        padding: 25px;
        border: 0px solid var(--warna-bingkai);
        border-radius: var(--bingkai);
    }

    .awalan {
        margin-top: 20px;
        width: 245px;
        min-height: 25px;
        padding: 12px;
        font-size: 13px;
        color: white;
        background: rgba(0, 0, 0, .5);
        border: 1px solid #fff;
        border-radius: 20px;
        display: flex;
        align-items: center;
        text-align: left
    }

    .awalan svg {
        margin-right: 15px;
        width: 25px;
        height: 25px;
        stroke: white
    }

    p {
        opacity: 0;
        color: var(--warna-teks);
        font-size: 15px;
        font-weight: 700;
        line-height: 1.4em;
        margin: 0px;
        text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);
        transform: scale(.1);
        transition: all .3s ease;
    }

    #spasi::before {
        content: "\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0\00a0"
    }

    #kalimat,
    #kalimatc {
        opacity: 1;
        transform: scale(1);
    }

    #kalimatc {
        font-size: 15px;
        font-weight: 700
    }

    #katajawab {
        font-weight: 400;
        margin: 0;
        display: none;
    }

    @keyframes rto {
        from {
            transform: scale(1);
        }

        to {
            transform: scale(1.1);
        }
    }

    @keyframes aniopa {
        0% {
            transform: scale(1);
        }

        50% {
            transform: scale(.75);
        }

        100% {
            transform: scale(1);
        }
    }

    #katabawah {
        transform: scale(.1);
        font-size: 30px;
        font-weight: 400
    }

    #katatiga {
        font-size: 18px;
    }

    #kataempat {
        font-size: 13px;
        font-weight: 400;
        text-align: right;
    }

    @keyframes rtf {
        from {
            transform: rotate(0deg);
        }

        to {
            transform: rotate(360deg);
        }
    }

    @keyframes rt {
        from {
            transform: scale(.9);
            /* transform: rotate(-5deg); */
        }

        to {
            transform: scale(1);
            /* transform: rotate(5deg); */
        }
    }

    #bq img {
        display: none;
        padding: 10px;
        width: 130px;
        height: 130px;
        margin: 20px 0 0 0;
    }

    #bq img:first-child {
        display: inline-flex
    }

    #akhiran {
        display: none;
        color: #FFC700;
        font-size: 14px;
        text-align: center;
        background: rgba(0, 0, 0, .55);
        text-shadow: 0px;
        padding: 10px;
        border-radius: var(--bingkai);
        line-height: 10px;
        transition: all .2s ease;
    }

    #akhiran:hover {
        transform: scale(.9);
        opacity: .5;
    }

    #pergeseran {
        opacity: 0;
        visibility: hidden;
        transition: all 1s ease;
        display: flex;
        flex-wrap: nowrap;
        align-items: flex-start;
        justify-content: flex-start;
        position: relative;
        max-width: 500px;
        padding: 0 20px;
        overflow-y: hidden;
        overflow-x: scroll;
        scroll-behavior: smooth;
        scroll-snap-type: x mandatory;
        -ms-overflow-style: none;
        -webkit-overflow-scrolling: touch
    }

    #pergeseran p {
        background: #003A76;
        color: white;
        border: 1px dashed #fff;
        border-radius: 8px;
        padding: 8px;
        display: flex;
        flex-wrap: nowrap;
        text-align: center;
        font-size: 16px;
        font-weight: 700;
        align-items: center;
        justify-content: center;
        flex-shrink: 0;
        width: 90%;
        min-height: 130px;
        margin: 0 15px 0 0;
        scroll-snap-align: center
    }

    #pergeseran>*:last-child {
        margin-right: 0
    }

    #pergeseran:after {
        content: '';
        display: block;
        flex-shrink: 0;
        align-self: stretch;
        padding-left: 20px
    }

    #pergeseran p b {
        display: block;
    }

    #pergeseran p b img {
        width: 80px;
        height: 80px;
        margin: 20px 0;
    }

    #tm {
        color: #FFB400;
        transition: all .5s ease;
    }

    #tm:hover {
        transform: scale(.7);
    }

    #idgeser {
        position: relative;
        top: 30vh;
        font-size: 17px;
        color: white
    }

    #contTom {
        opacity: 0;
        margin: 0;
        display: flex;
        align-items: left;
        list-style: none;
        transition: all 1s ease;
    }

    .button {
        cursor: pointer;
        display: inline-flex;
        align-items: center;
        margin: 0;
        margin: 12px 0 12px 0;
        transition: all .3s ease;
        padding: 10px;
        outline: 0;
        border: 1px solid var(--warna-bingkai);
        border-radius: var(--bingkai);
        line-height: 15px;
        background: var(--warna-bg);
        color: var(--warna-teks);
        font-size: 13px;
        font-weight: 700;
        white-space: nowrap;
        overflow: hidden;
        z-index: 1
    }

    .button:hover {
        transform: scale(.90);
        opacity: .98;
    }

    #buttonv2 {
        position: absolute;
        font-size: 15px;
        color: white;
        background: var(--warna-bg);
        padding: 10px;
        border-radius: 8px;
        line-height: 10px;
        text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);
        opacity: 0
    }

    .lovein {
        font-size: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        transition: all .3s ease;
    }

    .lovein svg {
        width: 80px;
        height: 80px;
        fill: #fefefe
    }

    .content2 {
        display: block;
        text-align: center;
        width: 100%;
        height: 180px;
        margin-top: 50px;
    }

    .content2>* {
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: 15px;
        font-size: 17px;
        color: white
    }

    .image img {
        border-radius: 10%;
        transform: scale(.1);
        transition: all .8s ease;
    }

    #k2 .image>* {
        margin-bottom: 40px;
    }

    #k2 {
        font-weight: 700;
        font-size: 17px;
        color: white;
        text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);
    }

    #final1 {
        transition: all 3s ease;
    }

    #idkirim {
        font-size: 13px;
        text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);
        color: white;
        transition: all .5s ease;
    }

    #idkirim {
        opacity: 0;
        visibility: hidden;
        margin-top: 100px
    }

    #idkirim:hover {
        transform: scale(.8);
    }

    .content2 {
        display: none;
    }

    #Content {
        animation-name: none;
        animation-duration: 3s;
        animation-iteration-count: infinite;
        position: relative;
        opacity: 0;
        margin-top: 50px;
        width: 100%;
        height: 180px
    }

    #Content>* {
        display: flex;
        align-items: center;
        text-align: center;
        justify-content: center;
        margin-top: 15px;
    }

    #Content img {
        display: none;
        box-shadow: 0 4px 30px rgba(255, 255, 255, 0.3);
        backdrop-filter: blur(5px);
        -webkit-backdrop-filter: blur(5px);
        width: 90px;
        height: 90px;
        background: rgba(255, 255, 255, 0.7);
        border: 1px solid rgba(255, 255, 255, 0.3);
        border-radius: 50%;
        padding: 10px;
        margin: 20px 0 0 0;
    }

    .swal2-modal>* {
        font-size: 16px
    }

    .swal2-title {
        line-height: 1.3em;
        margin-right: 20px;
        margin-left: 20px;
        font-size: 18px;
        text-align: center;
        padding: 15px 30px 0 30px;
    }

    .swal2-timer-progress-bar-container>* {
        opacity: .3;
        background: #007AFF;
        margin: 0 5px
    }

    .swal2-modal {
        background: rgba(255, 255, 255, 1);
        border: .7px solid #fff;
        border-radius: var(--bingkai);
        top: -60px;
    }

    .fa-heart {
        opacity: .18;
        color: white;
        font-size: 20px;
        position: absolute;
        animation: heartMove linear 1;
        top: -10vh;
        z-index: 0;
    }

    @keyframes heartMove {
        0% {
            transform: translateY(-10vh);
        }

        100% {
            transform: translateY(100vh);
        }
    }

    .overlay {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        z-index: 100;
    }

    .loading-message {
        font-size: 14px;
        font-weight: bold;
        color: white;
        text-align: center;
    }
