# liate-travel
<p>
做一個漢堡選單會員
關於我們（about)、景點一覽（spot)、山海漫遊、
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
