# liate-travel
會員登入失敗提示
訪客跟會員
<p>
做一個漢堡選單會員
關於我們（about)、景點一覽（spot-list)、山海漫遊(tour-guide)、旅遊體驗(experience)、相關資訊(information)
1、輪播圖換另一個頁面的
2、主要內容：
    1.活動公告：
    (2025/02/07～2025/2/23-2025桃園燈會)
    (2024/12/28～2025/03/02-彰化月影燈節)
    (2024/12/20～2025/03/02-屏東落山風藝術季)
    2.快速申請：
        解說導覽：鹽水、阿里山、九份、科工館
        山屋營地：苗栗-桃樂絲露營區、高雄溫德莊園
        潛水體驗：    
3、山海熱點：
    北：猴桐車站
    中：高美濕地
    南：阿里山國家森林遊樂園區、台南鹽水
    東：頭城、華源海濱公園
關於我們：
    1. 發掘台灣之美，為旅人打造專屬體驗
    2. 旅行不只是打卡——Liate，帶你發現大自然的美麗
    3. 你的旅遊靈感補給站——Liate，為探索而生
#mousewheel
var owl = $('.owl-carousel');
owl.owlCarousel({
    loop:true,
    nav:true,
    margin:10,
    responsive:{
        0:{
            items:1
        },
        600:{
            items:3
        },            
        960:{
            items:5
        },
        1200:{
            items:6
        }
    }
});
owl.on('mousewheel', '.owl-stage', function (e) {
    if (e.deltaY>0) {
        owl.trigger('next.owl');
    } else {
        owl.trigger('prev.owl');
    }
    e.preventDefault();
});    
刪除git資料夾：
Remove-Item -Recurse -Force .git
</p>
https://www.flaticon.com/free-sticker/tourist_11482694?term=travel&page=1&position=9&origin=search&related_id=11482694
主選單更改
<!-- 主選單 修改會員-->
    <nav class="navbar navbar-expand-xl shadow-sm position-sticky top-0 end-0 z-3 start-0 bg-blue">
        <div class="container-lg position-relative">
            <!-- 會員Logo -->
            <h1 class="navbar-brand col-xl-3 col-lg-9 col-md-8 px-xl-3 me-0 mb-0">
                <a class="navbar-brand  me-0" href="index.html" title="前往首頁">
                    <!-- 平板以上 -->
                    <img class="d-md-inline-block d-none" src="img/logo_rename.png" alt="莉艾特山海漫遊 Logo">
                    <!-- 手機板 -->
                    <img class="d-md-none d-inline-block" src="img/logo_md.svg" alt="莉艾特山海漫遊 Logo">
                    <span class="d-none">莉艾特山海漫遊</span> <!--xl 1200以上--->
                </a>
            </h1>
            <!-- 漢堡選單 -->
            <button class="navbar-toggler border-0" type="button" data-bs-toggle="collapse" data-bs-target="#main-menu"
                aria-controls="main-menu" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <!-- 連結 -->
            <div class="collapse navbar-collapse flex-fill justify-content-md-center  top-100 start-0 end-0 end-0 bg-blue py-lg-0 py-5"
                id="main-menu">
                <ul class="navbar-nav mb-2 mb-lg-0 text-center">
                    <li class="nav-item">
                        <a class="nav-link " href="#information" title="前往 相關資訊">公告資訊</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="spot-list.html" title="前往 景點一覽">景點一覽</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#tourist-hotspots" title="前往 山海熱點">山海熱點</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#apply" title="前往 線上申請">線上申請</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about" title="前往 關於我們">關於我們</a>
                    </li>
                    <!-- 會員 (僅手機和平板顯示) -->
                    <li class="nav-item d-xl-none">
                        <a href="javascript:;" title="點擊會員登入" data-bs-toggle="modal" data-bs-target="#exampleModal"
                            class="nav-link">
                            <i class="bi bi-person-heart"></i>
                            <span>會員登入</span>
                        </a>
                    </li>
                </ul>
            </div>
            <!-- 會員(僅電腦版顯示) -->
            <div class="d-none d-xl-flex align-items-center ms-auto text-decoration-none text-gr">
                <i class="bi bi-person-heart"></i>
                <a href="javascript:;" title="點擊會員登入" data-bs-toggle="modal" data-bs-target="#exampleModal">
                    <span class="d-md-inline-block d-none text-gr">會員登入</span>
                </a>
            </div>
        </div>
    </nav>