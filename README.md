# Psychologist1.0
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            width: 750px;
        }
        .head{
            background-color: #2D7053;
            height: 237px;
            width: auto;
            padding-top: 46px;
            padding-left: 37px;
        }
        .row{
            display: flex;
            flex-direction: row;
        }
        .circle{
            background-color: white;
            height: 144px;
            width: 144px;
            border-radius: 50%;
        }
        .text{
            height: 131px;
            width: 134px;
            margin-left: 57px;
            color: white;
            font-size: 20px;
            line-height: 10px;
        }
        span{
            background-color: white;
            border-radius: 20px;
            height: 15px;
            width: 87px;
            margin-top: 13px;
            margin-left: 249px;
            margin-right: 44px;
        }
        .column{
            display: flex;
            flex-direction: column;
        }
        .main{
            height: 470px;
            width: 100%;
            position: relative;
            max-width: 750px;
        }
        #room{
            height: inherit;
            width: inherit;
        }
        .btn1{
            background-color: rgba(203, 146, 35, 1);
            color: white;
            font-size: 20px;
            width: 344px;
            height: 77px;
            border: none;
            position: absolute;
            top: 80%;
            left: 25%
        }
        .main1{
            display: flex;
            flex-direction: row;
            padding-left: 35px;
            padding-top: 80px;
        }
        #portrait{
            height: 276px;
            width: 255px;
            border-radius: 50%;
        }
        .main1>div{
            margin-left: 68px;
            margin-top: 20px;
            font-size: 20px;
            width: 260px;
        }
        .info{
            margin-top: 46px;
            margin-left: 35px;
            margin-right: 126px;
            font-size: 20px;
        }
        #reasons{
            margin-top: 46px;
            margin-left: 35px;
            font-size: 40px;
        }
        ul{
            margin-top: 46px;
            margin-left: 35px;
            font-size: 20px;
        }
        .btn2{
            background-color: rgba(203, 146, 35, 1);
            color: white;
            font-size: 20px;
            width: 344px;
            height: 77px;
            border: none;
            margin-top: 42px;
            margin-left: 25%;
        }
        .footer{
            background-color: rgba(136, 136, 136, 1);
            width: auto;
            height: 156px;
            padding-top: 46px;
            padding-left: 37px;
            padding-bottom: 28px;
            margin-top: 47px;
        }
        .footer>.row>p{
            color: white;
            margin-left: 183px;
            margin-top: 104px;
            font-size: 15px;
        }
        .footer>.row>div>p{
            color: white;
            margin-top: 20px;
            margin-left: 46px;
            font-size: 15px;
            line-height: 43px;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <div class="head">
        <div class="row">
            <div class="circle"></div>
            <div class="text">
                <p>Кабинет</p>
                <p>Психолога</p>
                <p>Имени</p>
                <p>Фамилии</p>
            </div> 
            <div class="column">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </div>
    <!-- Main -->
    <div class="main">
        <img src="Room.png" alt="room" id="room">
        <button class="btn1" type="button">ЗАПИСАТЬСЯ НА ПРИЕМ</button>
    </div>
    <div class="main1">
        <img src="154-9254.png" alt="Psychologist" id="portrait">
        <div>
            <h1>Имя Фамилия</h1>
            <p>психотерапевт такой то специализации</p>
        </div>
    </div>
    <p class="info">
        Тут психолог рассказывает о своей специалзации, 
        своем опыте, приводит успешные кейсы и рассказывает, 
        что она лучший специалист в городе
        Тут психолог рассказывает о своей специалзации, 
        своем опыте, приводит успешные кейсы и рассказывает, 
        что она лучший специалист в городе
    </p>
    <h1 id="reasons">Причины посетить психотерапевта</h1>
    <ul>
        <li>причина номер раз</li>
        <li>причина номер два</li>
        <li>причина номер три</li>
        <li>причина номер четыре</li>
        <li>причина номер пять</li>
        <li>причина номер шесть</li>
        <li>причина номер семь</li>
    </ul>
    <button class="btn2" type="button">ЗАПИСАТЬСЯ НА ПРИЕМ</button>
    <!-- Footer -->
    <div class="footer">
        <div class="row">
            <div class="circle"></div>
            <p>ул. Кудрявцева 37, каб. 17</p>
            <div class="column">
               <p>+38(099)9519551</p>
                <p>psycho@gmail.com</p>
            </div>
        </div>
    </div>

</body>
</html>
