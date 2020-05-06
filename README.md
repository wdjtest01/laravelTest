# 실행
```
php artisan serve
```

***

## git clone
```
composer install
npm install
```

***

### 생성 [PHP 7.3.12 / Composer 1.9.1]
```
composer create-project --prefer-dist laravel/laravel laravelVueTest
```

### 스캐폴딩 [node v12.13.1 / npm 6.12.1]
> npm run dev 에러 cross-env 설치
```
composer require laravel/ui --dev
php artisan ui vue
npm install
npm install --global cross-env  
npm run dev
```

### 연동 테스트
> /resources/views/welcome.blade.php 파일
```
<div id='app'>
  <example-component></example-component>
</div>
<script src="{{ asset('js/app.js') }}"></script>
```