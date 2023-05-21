# HTML

    <div class="box">
        <div class="lightbar"></div>
        <div class="topLayer"></div>
        <h2>DRL Ystav</h2>
    </div>

# CSS Syntaxe

@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@600;700&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Nunito', sans-serif;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #000;
    overflow: hidden;
}
.box{
    position: relative;
    width: 600px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.box h2{
    color: #fff;
    font-size: 5em;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-shadow: 0 0 10px #00b3ff,
                0 0 20px #00b3ff, 
                0 0 40px #00b3ff,
                0 0 80px #00b3ff,
                0 0 120px #00b3ff;
}
.lightbar{
    position: absolute;
    top: 0;
    left: 0;
    width: 10px;
    height: 100%;
    border-radius: 10px;
    background: #fff;
    z-index: 2;
    box-shadow: 0 0 10px #00b3ff,
                0 0 20px #00b3ff, 
                0 0 40px #00b3ff,
                0 0 80px #00b3ff,
                0 0 120px #00b3ff;
    animation: animatelightbar 5s linear infinite;
}
@keyframes animatelightbar{
    0%,5%{
        transform: scaleY(0) translateX(0);
    }
    10%{
        transform: scaleY(1) translateX(0);
    }
    90%{
        transform: scaleY(1) translateX(calc(600px - 10px));
    }
    95%,100%{
        transform: scaleY(0) translateX(calc(600px - 10px));
    }
}
.topLayer{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #000;
    animation: animatetopLayer 10s linear infinite;
}
@keyframes animatetopLayer{
    0%,2.5%{
        transform: translateX(0);
    }
    5%{
        transform: translateX(0);
    }
    45%{
        transform: translateX(calc(100%));
    }
    47.5%,50%{
        transform: translateX(calc(100%));
    }

    50.001%,52.5%{
        transform: translateX(-100%);
    }
    55%{
        transform: translateX(-100%);
    }
    95%{
        transform: translateX(calc(0%));
    }
    97.5%,100%{
        transform: translateX(calc(0%));
    }
}


# View
![DRL](https://github.com/Vatsy145/Neon-Text-/assets/80814790/df3690c3-27f1-42f2-9ae2-1afcc1c9b528)

# NB
If the stylesheet is not in order, use Beautify Extension

![Microsoft VisualStudio Services Icons](https://github.com/Vatsy145/Neon-Text-/assets/80814790/f22aa858-3527-4854-9e70-4236be34b4e1)
