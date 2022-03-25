# 내일의 집

## 1. GNB

- 로그인을 한 경우

```html
<div class="gnb-btn-group">
  <button
    class="gnb-icon-btn is-search lg-hidden"
    type="button"
    aria-label="내일의 집 검색창 열기"
  >
    <i class="ic-search"></i>
  </button>

  <a
    href="#"
    class="gnb-icon-btn sm-hidden"
    aria-label="스크랩북 페이지로 이동하기"
  >
    <i class="ic-bookmark"></i>
  </a>

  <a
    href="#"
    class="gnb-icon-btn sm-hidden"
    aria-label="내 소식 페이지로 이동하기"
  >
    <i class="ic-bell"></i>
  </a>

  <a
    href="#"
    class="gnb-icon-btn is-cart"
    aria-label="장바구니 페이지로 이동하기"
  >
    <i class="ic-cart"></i>
    <strong class="badge">3</strong>
  </a>

  <button
    type="button"
    class="gnb-avatar-btn sm-hidden"
    aria-label="마이 매뉴 열기 버튼"
  >
    <div class="avatar-32">
      <img src="./assets/images/img-user-01.jpg" alt="사달라 아저씨" />
    </div>
  </button>
</div>
```

- 로그인을 하지 않은 경우

```html
<div class="gnb-btn-group">
  <button
    class="gnb-icon-btn is-search lg-hidden"
    type="button"
    aria-label="내일의 집 검색창 열기"
  >
    <i class="ic-search"></i>
  </button>
  <a
    href="#"
    class="gnb-icon-btn is-cart"
    aria-label="장바구니 페이지로 이동하기"
  >
    <i class="ic-cart"></i>
  </a>
  <div class="gnb-auth sm-hidden">
    <a href="/">로그인</a>
    <a href="/">회원가입</a>
  </div>
</div>
```
