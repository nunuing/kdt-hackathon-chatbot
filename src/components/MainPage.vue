<template>

    <body>
        <div class="main_title">
            <img id="chatbot_logo" src="../assets/icon/chatbot.png">
            <div class="title_content"><span id="title_point">'오손녀'</span>가<br>
                서류 발급을 도와드릴게요!
            </div>
        </div>
        <div class="main_contents">
            <table>
                <tbody>
                    <tr class="title_tr">
                        <td class="content_title">
                            " 원하는 항목을 선택해주세요 "
                        </td>
                    </tr>
                    <tr class="btn_tr">
                        <td>
                            <div class="big_btn main_title btn_9BCB3C">
                                <div class="btn_content">
                                    기다림 없이 <br>
                                    서류 발급을 할 수 있어요!
                                </div>
                                <img class="btn_image" src="../assets/icon/folder.png">
                            </div>
                        </td>
                    </tr>
                    <tr class="btn_tr">
                        <td>
                            <div class="big_btn main_title btn_6B9E5B">
                                <img class="btn_image" src="../assets/icon/talking.png">
                                <div class="btn_content">
                                    대화를 통해 <br>
                                    필요한 서류를 찾아드려요!
                                </div>
                            </div>
                        </td>
                    </tr>
                </tbody>
            </table>
        </div>
        <table class="btn_table">
                <tbody>
                    <tr>
                        <td>
                            <div class="small_btn">
                                직원호출
                            </div>
                        </td>
                        <td>
                            <div class="small_btn">
                                사용법 보기
                            </div>
                        </td>
                    </tr>
                </tbody>
            </table>
    </body>
</template>

<style>
    .main_title {
        width: 720px;
        display: flex;
        text-align: left;
        align-items: flex-end;
        justify-content: center;
    }
    #chatbot_logo {
        width: 160px;
        height: 160px;
        margin-bottom: -3px;
    }
    #title_point{
        font-family: 학교안심나들이체;
        color: #347928;
        font-size: 60px;
    }
    .title_content {
        font-family: 눈누기초고딕;
        font-size: 40px;
        display: inline-block; 
        margin: 0px 38px 38px;
    }
    .main_contents {
        width: 720px;
        height: 790px;
        background-color: #ECF6D3;
        border-radius: 45px;
    }
    .main_contents table {
        margin: auto;
    }
    .content_title {
        font-size: 40px;
        font-family: 플라이트산스;
        color: #41493B;
    }
    .big_btn {
        height: 221px;
        width: 604px;
        border-radius: 20px;
        box-shadow : 5px 5px 5px rgb(0, 0, 0, 0.25);
    }
    .btn_image {
        width: 175px;
        height: 175px;
        padding-bottom: 20px;
    }
    .btn_content {
        font-family: 플라이트산스;
        width: 360px;
        font-size: 32px;
        color: white;
        padding-bottom: 29px;
    }
    .btn_9BCB3C {
        background-color: #9BCB3C;
    }
    .btn_6B9E5B {
        background-color: #6B9E5B;
    }
    .title_tr {
        height: 200px;
    }
   .btn_tr {
        height: 260px;
    }
    .small_btn {
        width: 261px;
        height: 128px;
        border-radius: 13px;
        font-size: 40px;
        font-family: 플라이트산스;
        color: #0E2C09;
        background-color: #EFF1BC;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: auto;
    }
    .btn_table {
        margin: 70px auto auto auto;
    }
    .btn_table td {
        width: 320px;
    }
</style>