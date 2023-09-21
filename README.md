# 전기차 충전소 


# 1등이조 - CafeMoa

<p align="center">
<img width="60%" src="https://user-images.githubusercontent.com/90763140/212879841-354fda8e-b566-49eb-85cc-b305843ccce6.png">
</p>

<br><br>

# CafeMoa 소개

**카페모아**의 기획 의도는 지난 10년간
프랜차이즈 및 개인카페들이 우후죽순으로 늘어나고 있습니다.

개인카페, 동네 카페의 경우에는 다른 커피점들과는 달리 뚜렷한 홍보수단이 없어 어려움을 겪고,
프랜차이즈에 밀려 폐업을 하기도 한다.

그래서 이 카페들을 위한 홍보망을 구축하고, 이 사이트를 사용하는 고객들은 쿠폰서비스를 제공받아
이득을 얻을 수 있도록 하기 위해 이 서비스를 기획하고, 개발을 하게 되었습니다.

# 배포주소



<br><br>

# 팀원소개

<p align="center">
<img width="60%" src="https://user-images.githubusercontent.com/90763140/212874301-21959fd3-d114-4cb3-a6bd-498cadf955af.png">
<img width="60%" src="https://user-images.githubusercontent.com/90763140/212874414-d37f8b41-6c29-4be1-8d5e-77a65bb45afa.png">
</p>

# 기술스택

<p align="center">
<img width="60%" src="https://user-images.githubusercontent.com/90763140/212874771-fd214c1a-4189-40b7-a50a-1f773392bcea.png">
</p>

# Data Flow

<p align="center">
<img width="60%" src="https://user-images.githubusercontent.com/90763140/212875029-999a18ff-d389-4e72-8dbf-0aef8a38c579.png">
</p>

# ERD

<p align="center">
<img width="60%" src="![ERD](https://github.com/kims26/TeamProject/assets/114653761/7fbff21f-6e00-456f-aa3e-c42e63bfec76)
>
</p>

# API-DOCS

<p align="center">
<img width="60%" src="https://user-images.githubusercontent.com/90763140/212875454-f47ed15d-47f3-41b9-99e2-2f83826c999c.png">
</p>

# 서버 폴더구조

```

```
TeamFinalProject
├─ .DS_Store
├─ .gitignore
├─ .mvn
│  └─ wrapper
│     ├─ maven-wrapper.jar
│     └─ maven-wrapper.properties
├─ DB.sql
├─ bin
│  ├─ .gitignore
│  ├─ .mvn
│  │  └─ wrapper
│  │     ├─ maven-wrapper.jar
│  │     └─ maven-wrapper.properties
│  ├─ mvnw
│  ├─ mvnw.cmd
│  ├─ pom.xml
│  └─ src
│     ├─ main
│     │  ├─ java
│     │  │  └─ FinalProject
│     │  │     └─ demo_final
│     │  │        ├─ DemoFinalApplication.class
│     │  │        ├─ controller
│     │  │        │  └─ MainController.class
│     │  │        ├─ dao
│     │  │        ├─ main.js
│     │  │        └─ vo
│     │  ├─ resources
│     │  │  ├─ application.properties
│     │  │  ├─ mybatis
│     │  │  │  └─ mapper
│     │  │  ├─ static
│     │  │  │  └─ index.html
│     │  │  └─ templates
│     │  └─ webapp
│     │     ├─ WEB-INF
│     │     │  └─ views
│     │     │     └─ main
│     │     ├─ css
│     │     │  ├─ main.css
│     │     │  ├─ main_footer.css
│     │     │  ├─ main_header.css
│     │     │  ├─ main_header_responsive.css
│     │     │  └─ reset.css
│     │     ├─ images
│     │     │  └─ search.png
│     │     └─ main
│     │        └─ main.jsp
│     └─ test
│        └─ java
│           └─ FinalProject
│              └─ demo_final
│                 └─ DemoFinalApplicationTests.class
├─ min2
│  ├─ .DS_Store
│  ├─ .git
│  │  ├─ HEAD
│  │  ├─ config
│  │  ├─ description
│  │  ├─ hooks
│  │  │  ├─ applypatch-msg.sample
│  │  │  ├─ commit-msg.sample
│  │  │  ├─ fsmonitor-watchman.sample
│  │  │  ├─ post-update.sample
│  │  │  ├─ pre-applypatch.sample
│  │  │  ├─ pre-commit.sample
│  │  │  ├─ pre-merge-commit.sample
│  │  │  ├─ pre-push.sample
│  │  │  ├─ pre-rebase.sample
│  │  │  ├─ pre-receive.sample
│  │  │  ├─ prepare-commit-msg.sample
│  │  │  ├─ push-to-checkout.sample
│  │  │  ├─ sendemail-validate.sample
│  │  │  └─ update.sample
│  │  ├─ index
│  │  ├─ info
│  │  │  └─ exclude
│  │  ├─ logs
│  │  │  ├─ HEAD
│  │  │  └─ refs
│  │  │     ├─ heads
│  │  │     │  └─ main
│  │  │     └─ remotes
│  │  │        └─ origin
│  │  │           └─ HEAD
│  │  ├─ objects
│  │  │  ├─ info
│  │  │  └─ pack
│  │  │     ├─ pack-4c9c06c468f39654667d87e5c3ececb6b01863ee.idx
│  │  │     ├─ pack-4c9c06c468f39654667d87e5c3ececb6b01863ee.pack
│  │  │     └─ pack-4c9c06c468f39654667d87e5c3ececb6b01863ee.rev
│  │  ├─ packed-refs
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ main
│  │     ├─ remotes
│  │     │  └─ origin
│  │     │     └─ HEAD
│  │     └─ tags
│  └─ README.md
├─ mvnw
├─ mvnw.cmd
├─ pom.xml
└─ src
   ├─ .DS_Store
   ├─ main
   │  ├─ .DS_Store
   │  ├─ java
   │  │  ├─ .DS_Store
   │  │  ├─ demo_final
   │  │  │  ├─ .DS_Store
   │  │  │  ├─ DemoFinalApplication.java
   │  │  │  ├─ controller
   │  │  │  │  ├─ .DS_Store
   │  │  │  │  ├─ AdminController.java
   │  │  │  │  ├─ ApiOperation.java
   │  │  │  │  ├─ BoardController.java
   │  │  │  │  ├─ CartController.java
   │  │  │  │  ├─ ChargeController.java
   │  │  │  │  ├─ CommentBoardController.java
   │  │  │  │  ├─ FavoriteController.java
   │  │  │  │  ├─ KakaoPayController.java
   │  │  │  │  ├─ LoginController.java
   │  │  │  │  ├─ MailController.java
   │  │  │  │  ├─ MainController.java
   │  │  │  │  ├─ MemberController.java
   │  │  │  │  ├─ NaverLoginApi.java
   │  │  │  │  ├─ NaverLoginBO.java
   │  │  │  │  ├─ OwnerController.java
   │  │  │  │  ├─ PaymentController.java
   │  │  │  │  └─ ProductController.java
   │  │  │  ├─ dao
   │  │  │  │  ├─ AdminDao.java
   │  │  │  │  ├─ BoardDao.java
   │  │  │  │  ├─ CartDao.java
   │  │  │  │  ├─ CategoryDao.java
   │  │  │  │  ├─ CommentBoardDao.java
   │  │  │  │  ├─ DeliveryDao.java
   │  │  │  │  ├─ FavoriteDao.java
   │  │  │  │  ├─ MemberDao.java
   │  │  │  │  ├─ OwnerDao.java
   │  │  │  │  ├─ PaymentDao.java
   │  │  │  │  └─ ProductDao.java
   │  │  │  ├─ service
   │  │  │  │  ├─ KakaoPayService.java
   │  │  │  │  └─ Mailservice.java
   │  │  │  └─ vo
   │  │  │     ├─ AdminVo.java
   │  │  │     ├─ Amount.java
   │  │  │     ├─ BoardVo.java
   │  │  │     ├─ CartVo.java
   │  │  │     ├─ CategoryVo.java
   │  │  │     ├─ ChargeVo.java
   │  │  │     ├─ CommentBoardVo.java
   │  │  │     ├─ DeliveryVo.java
   │  │  │     ├─ FavoriteVo.java
   │  │  │     ├─ KakaoApproveResponse.java
   │  │  │     ├─ KakaoReadyResponse.java
   │  │  │     ├─ MailVo.java
   │  │  │     ├─ MemberVo.java
   │  │  │     ├─ OwnerVo.java
   │  │  │     ├─ PaymentParam.java
   │  │  │     ├─ PaymentVo.java
   │  │  │     └─ ProductVo.java
   │  │  └─ util
   │  │     ├─ ChargeSearchUtils.java
   │  │     ├─ MyConstant.java
   │  │     ├─ MyDistance.java
   │  │     └─ Paging.java
   │  ├─ resources
   │  │  ├─ .DS_Store
   │  │  ├─ application.properties
   │  │  ├─ mybatis
   │  │  │  ├─ .DS_Store
   │  │  │  └─ mapper
   │  │  │     ├─ admin.xml
   │  │  │     ├─ board.xml
   │  │  │     ├─ cart.xml
   │  │  │     ├─ category.xml
   │  │  │     ├─ commentboard.xml
   │  │  │     ├─ delivery.xml
   │  │  │     ├─ favorite.xml
   │  │  │     ├─ member.xml
   │  │  │     ├─ owner.xml
   │  │  │     ├─ payment.xml
   │  │  │     └─ product.xml
   │  │  ├─ static
   │  │  │  └─ index.html
   │  │  └─ templates
   │  └─ webapp
   │     ├─ .DS_Store
   │     ├─ WEB-INF
   │     │  ├─ .DS_Store
   │     │  └─ views
   │     │     ├─ admin
   │     │     │  ├─ admin_chart.jsp
   │     │     │  ├─ admin_footer.jsp
   │     │     │  ├─ admin_grade.jsp
   │     │     │  ├─ admin_grade_list.jsp
   │     │     │  ├─ admin_insert_form.jsp
   │     │     │  ├─ admin_list.jsp
   │     │     │  ├─ admin_login_form.jsp
   │     │     │  ├─ admin_mem_grade.jsp
   │     │     │  ├─ admin_mem_grade_list.jsp
   │     │     │  ├─ admin_modify_form.jsp
   │     │     │  ├─ admin_o_grade.jsp
   │     │     │  ├─ admin_o_grade_list.jsp
   │     │     │  ├─ admin_sidebar.jsp
   │     │     │  └─ admin_topbar.jsp
   │     │     ├─ board
   │     │     │  ├─ board_insert_form.jsp
   │     │     │  ├─ board_list.jsp
   │     │     │  ├─ board_list2.jsp
   │     │     │  ├─ board_modify_form.jsp
   │     │     │  ├─ board_reply_form.jsp
   │     │     │  ├─ board_view.jsp
   │     │     │  └─ comment_list.jsp
   │     │     ├─ category
   │     │     │  ├─ a_type_category.jsp
   │     │     │  ├─ b_type_category.jsp
   │     │     │  └─ c_type_category.jsp
   │     │     ├─ charge
   │     │     │  ├─ charge_map.jsp
   │     │     │  ├─ charge_test.jsp
   │     │     │  └─ f_charger_list.jsp
   │     │     ├─ main
   │     │     │  ├─ footer.jsp
   │     │     │  ├─ header.jsp
   │     │     │  ├─ m_menu.jsp
   │     │     │  └─ main.jsp
   │     │     ├─ member
   │     │     │  ├─ member_insert_form.jsp
   │     │     │  ├─ member_login_form.jsp
   │     │     │  ├─ member_modify_form.jsp
   │     │     │  ├─ member_mypage.jsp
   │     │     │  ├─ member_naver_insert_form.jsp
   │     │     │  └─ product_order.jsp
   │     │     ├─ naver
   │     │     │  ├─ naverLogin.jsp
   │     │     │  └─ naverSuccess.jsp
   │     │     ├─ owner
   │     │     │  ├─ admin_footer.jsp
   │     │     │  ├─ owner_chart.jsp
   │     │     │  ├─ owner_insert_form.jsp
   │     │     │  ├─ owner_insert_msg.jsp
   │     │     │  ├─ owner_list.jsp
   │     │     │  ├─ owner_login_form.jsp
   │     │     │  ├─ owner_modify_form.jsp
   │     │     │  ├─ owner_order.jsp
   │     │     │  ├─ owner_pay.jsp
   │     │     │  ├─ owner_pay_list.jsp
   │     │     │  ├─ owner_pay_succ.jsp
   │     │     │  ├─ owner_product_list.jsp
   │     │     │  ├─ owner_sales_rate.jsp
   │     │     │  ├─ owner_sidebar.jsp
   │     │     │  ├─ owner_topbar.jsp
   │     │     │  └─ owner_wait.jsp
   │     │     ├─ payment
   │     │     │  ├─ payment_list.jsp
   │     │     │  └─ payment_success.jsp
   │     │     ├─ product
   │     │     │  ├─ cart_list.jsp
   │     │     │  ├─ product_cart_payment_list.jsp
   │     │     │  ├─ product_insert_form.jsp
   │     │     │  ├─ product_list.jsp
   │     │     │  ├─ product_main_page.jsp
   │     │     │  ├─ product_modify_form.jsp
   │     │     │  ├─ product_page_form.jsp
   │     │     │  └─ product_test.jsp
   │     │     └─ search
   │     │        └─ search_main.jsp
   │     ├
   │     ├─ finaljs
   │     │  └─ finaljs
   │     │     ├─ accordions.js
   │     │     ├─ bootstrap.min.js
   │     │     ├─ custom.js
   │     │     ├─ datepicker.js
   │     │     ├─ imgfix.min.js
   │     │     ├─ isotope.js
   │     │     ├─ jquery-2.1.0.min.js
   │     │     ├─ jquery.counterup.min.js
   │     │     ├─ lightbox.js
   │     │     ├─ owl-carousel.js
   │     │     ├─ popper.js
   │     │     ├─ quantity.js
   │     │     ├─ scrollreveal.min.js
   │     │     ├─ slick.js
   │     │     └─ waypoints.min.js
   │     ├─
   │     ├─ js
   │     │  ├─ bootstrap.bundle.min.js
   │     │  ├─ custom.js
   │     │  ├─ final.js
   │     │  ├─ jquery-1.11.0.min.js
   │     │  ├─ jquery-migrate-1.2.1.min.js
   │     │  ├─ slick.min.js
   │     │  ├─ templatemo.js
   │     │  └─ templatemo.min.js
   │     ├
   │     ├─ resources
   │     │  
   │     │  ├─ js
   │     │  │  ├─ demo
   │     │  │  │  ├─ chart-area-demo.js
   │     │  │  │  ├─ chart-bar-demo.js
   │     │  │  │  ├─ chart-pie-demo.js
   │     │  │  │  └─ datatables-demo.js
   │     │  │  ├─ sb-admin-2.js
   │     │  │  └─ sb-admin-2.min.js
   │     │  ├─ package-lock.json
   │     │  ├─ package.json
   │     │  ├─ sample_data.json
   │     │  ├─ scss
   │     │  │  ├─ _buttons.scss
   │     │  │  ├─ _cards.scss
   │     │  │  ├─ _charts.scss
   │     │  │  ├─ _dropdowns.scss
   │     │  │  ├─ _error.scss
   │     │  │  ├─ _footer.scss
   │     │  │  ├─ _global.scss
   │     │  │  ├─ _login.scss
   │     │  │  ├─ _mixins.scss
   │     │  │  ├─ _navs.scss
   │     │  │  ├─ _utilities.scss
   │     │  │  ├─ _variables.scss
   │     │  │  ├─ navs
   │     │  │  │  ├─ _global.scss
   │     │  │  │  ├─ _sidebar.scss
   │     │  │  │  └─ _topbar.scss
   │     │  │  ├─ sb-admin-2.scss
   │     │  │  └─ utilities
   │     │  │     ├─ _animation.scss
   │     │  │     ├─ _background.scss
   │     │  │     ├─ _border.scss
   │     │  │     ├─ _display.scss
   │     │  │     ├─ _progress.scss
   │     │  │     ├─ _rotate.scss
   │     │  │     └─ _text.scss
   │     │  └─ vendor
   │     │     ├─ bootstrap
   │     │     │  ├─ js
   │     │     │  │  ├─ bootstrap.bundle.js
   │     │     │  │  ├─ bootstrap.bundle.js.map
   │     │     │  │  ├─ bootstrap.bundle.min.js
   │     │     │  │  ├─ bootstrap.bundle.min.js.map
   │     │     │  │  ├─ bootstrap.js
   │     │     │  │  ├─ bootstrap.js.map
   │     │     │  │  ├─ bootstrap.min.js
   │     │     │  │  └─ bootstrap.min.js.map
   │     │     │  └─ scss
   │     │     │     ├─ _alert.scss
   │     │     │     ├─ _badge.scss
   │     │     │     ├─ _breadcrumb.scss
   │     │     │     ├─ _button-group.scss
   │     │     │     ├─ _buttons.scss
   │     │     │     ├─ _card.scss
   │     │     │     ├─ _carousel.scss
   │     │     │     ├─ _close.scss
   │     │     │     ├─ _code.scss
   │     │     │     ├─ _custom-forms.scss
   │     │     │     ├─ _dropdown.scss
   │     │     │     ├─ _forms.scss
   │     │     │     ├─ _functions.scss
   │     │     │     ├─ _grid.scss
   │     │     │     ├─ _images.scss
   │     │     │     ├─ _input-group.scss
   │     │     │     ├─ _jumbotron.scss
   │     │     │     ├─ _list-group.scss
   │     │     │     ├─ _media.scss
   │     │     │     ├─ _mixins.scss
   │     │     │     ├─ _modal.scss
   │     │     │     ├─ _nav.scss
   │     │     │     ├─ _navbar.scss
   │     │     │     ├─ _pagination.scss
   │     │     │     ├─ _popover.scss
   │     │     │     ├─ _print.scss
   │     │     │     ├─ _progress.scss
   │     │     │     ├─ _reboot.scss
   │     │     │     ├─ _root.scss
   │     │     │     ├─ _spinners.scss
   │     │     │     ├─ _tables.scss
   │     │     │     ├─ _toasts.scss
   │     │     │     ├─ _tooltip.scss
   │     │     │     ├─ _transitions.scss
   │     │     │     ├─ _type.scss
   │     │     │     ├─ _utilities.scss
   │     │     │     ├─ _variables.scss
   │     │     │     ├─ bootstrap-grid.scss
   │     │     │     ├─ bootstrap-reboot.scss
   │     │     │     ├─ bootstrap.scss
   │     │     │     
   │     │     │     └─ vendor
   │     │     │        └─ _rfs.scss
   │     │     ├─ chart.js
   │     │     │  ├─ Admin_chart.js
   │     │     │  ├─ Chart.bundle.js
   │     │     │  ├─ Chart.bundle.min.js
   │     │     │  ├─ Chart.js
   │     │     │  └─ Chart.min.js
   │     │     ├─ datatables
   │     │     │  ├─ dataTables.bootstrap4.css
   │     │     │  ├─ dataTables.bootstrap4.js
   │     │     │  ├─ dataTables.bootstrap4.min.css
   │     │     │  ├─ dataTables.bootstrap4.min.js
   │     │     │  ├─ jquery.dataTables.js
   │     │     │  └─ jquery.dataTables.min.js
   │     │     ├─ fontawesome-free
   │     │     │  ├─ LICENSE.txt
   │     │     │  ├─ attribution.js
   │     │     │  ├─ css
   │     │     │  │  ├─ all.css
   │     │     │  │  ├─ all.min.css
   │     │     │  │  ├─ brands.css
   │     │     │  │  ├─ brands.min.css
   │     │     │  │  ├─ fontawesome.css
   │     │     │  │  ├─ fontawesome.min.css
   │     │     │  │  ├─ regular.css
   │     │     │  │  ├─ regular.min.css
   │     │     │  │  ├─ solid.css
   │     │     │  │  ├─ solid.min.css
   │     │     │  │  ├─ svg-with-js.css
   │     │     │  │  ├─ svg-with-js.min.css
   │     │     │  │  ├─ v4-shims.css
   │     │     │  │  └─ v4-shims.min.css
   │     │     │  ├─ js
   │     │     │  │  ├─ all.js
   │     │     │  │  ├─ all.min.js
   │     │     │  │  ├─ brands.js
   │     │     │  │  ├─ brands.min.js
   │     │     │  │  ├─ conflict-detection.js
   │     │     │  │  ├─ conflict-detection.min.js
   │     │     │  │  ├─ fontawesome.js
   │     │     │  │  ├─ fontawesome.min.js
   │     │     │  │  ├─ regular.js
   │     │     │  │  ├─ regular.min.js
   │     │     │  │  ├─ solid.js
   │     │     │  │  ├─ solid.min.js
   │     │     │  │  ├─ v4-shims.js
   │     │     │  │  └─ v4-shims.min.js
   │     │     │  ├─ less
   │     │     │  │  ├─ _animated.less
   │     │     │  │  ├─ _bordered-pulled.less
   │     │     │  │  ├─ _core.less
   │     │     │  │  ├─ _fixed-width.less
   │     │     │  │  ├─ _icons.less
   │     │     │  │  ├─ _larger.less
   │     │     │  │  ├─ _list.less
   │     │     │  │  ├─ _mixins.less
   │     │     │  │  ├─ _rotated-flipped.less
   │     │     │  │  ├─ _screen-reader.less
   │     │     │  │  ├─ _shims.less
   │     │     │  │  ├─ _stacked.less
   │     │     │  │  ├─ _variables.less
   │     │     │  │  ├─ brands.less
   │     │     │  │  ├─ fontawesome.less
   │     │     │  │  ├─ regular.less
   │     │     │  │  ├─ solid.less
   │     │     │  │  └─ v4-shims.less
   │     │     │  ├─ metadata
   │     │     │  │  ├─ categories.yml
   │     │     │  │  ├─ icons.yml
   │     │     │  │  ├─ shims.yml
   │     │     │  │  └─ sponsors.yml
   │     │     │  ├─ package.json
   │     │     │  
   │     │     ├─ jquery
   │     │     │  ├─ jquery.js
   │     │     │  ├─ jquery.min.js
   │     │     │  ├─ jquery.min.map
   │     │     │  ├─ jquery.slim.js
   │     │     │  ├─ jquery.slim.min.js
   │     │     │  └─ jquery.slim.min.map
   │     │     └─ jquery-easing
   │     │        ├─ jquery.easing.compatibility.js
   │     │        ├─ jquery.easing.js
   │     │        └─ jquery.easing.min.js
   │    
   │    
   └─ test
      └─ java
         └─ FinalProject
            └─ demo_final
               └─ DemoFinalApplicationTests.java

```
