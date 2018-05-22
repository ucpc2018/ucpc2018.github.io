---
layout: default
---

<div class="main-pic-wrapper">
  <img id="main-pic" src="">
  <div class="main-pic-overlay"></div>
  <div class="main-pic-overlay-text">
    전국 대학생 프로그래밍 대회 동아리 연합<br />
    여름 대회 2018
  </div>
</div>

## UCPC 2018

UCPC는 전국 대학생 프로그래밍 대회 동아리 연합(이하 전대프연)에서 진행하는 여름 대회입니다.
2011년 제1회 UCPC를 시작으로 올해 제7회 UCPC를 준비하고 있습니다.

올해 대회는 총 상품 600만원 규모에
ACM-ICPC 대전 리저널과 유사한 형식으로 온라인 예선, 본선이 나눠져 진행됩니다.

ACM-ICPC를 준비하는 학생, 프로그래밍 대회에 관심이 있는 학생, 그냥 참가하고 싶은 학생 모두에게
좋은 경험이 될 것이니 많이 기대해주세요!

## 대회 일정

 * 참가 접수 : **2018년 5월 22일 ~ 6월 15일**
 * 온라인 예선 : **2018년 7월 14일 (토) 14:00 ~ 17:00**
 * 본선 : **2018년 7월 29일 (일) 10:00 ~ 19:00**

## 참가 신청

현재 참가팀 신청을 받고 있습니다. 아래 링크에 들어가 신청서를 작성해주시면 됩니다.

[참가 신청서](https://goo.gl/forms/AFmMCbTm8J9S5bea2)

참가와 관련된 안내는 대회 안내 페이지를 참고해주세요.


<script type="text/javascript">
  function lpad(num, pad_str, len) {
    var str = num.toString();
    while (str.length < len) {
      str = pad_str + str;
    }
    return str;
  }
  window.onload = function () {
    var picture_num = Math.floor(Math.random() * 11);
    var picture_name = 'main-pic-' + lpad(picture_num, '0', 2) + '.jpg';
    var path = '{{ "/assets/" | relative_url }}' + picture_name;
    document.getElementById('main-pic').src = path;
  };
</script>
