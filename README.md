# My self-study process - Flutter

## 1. Intro

Xin chào các bạn! Đây là bài viết thứ 3 của mình về Flutter. Bài viết hôm nay sẽ không có code mà mình sẽ chia sẻ về quá trình tự học Flutter của mình và những tài liệu mình đã dùng để những ai cũng có mong muốn tự tìm tòi như mình có thêm chút kinh nghiệm. 

> Có vẻ hơi ngược ngược thứ tự tí vì lẽ ra đây phải là bài thứ nhất chứ nhỉ! Nhưng mà mình viết theo cảm hứng nên hơi lộn xộn vậy. Ahihi!

Về bản thân mình thì mọi người có thể đọc qua tại [đây](https://github.com/vanle57).



## 2. Giới thiệu sơ lược về Flutter

Flutter là 1 framework được phát triển trên ngôn ngữ lập trình Dart. Flutter cho phép bạn có thể sử dụng 1 base code và build lên nhiều nền tảng khác nhau, bao gồm:

- iOS

- Android

- Web

- Windows, MacOS, Linux apps

Với mục đích hướng tới việc phát triển phần mềm trên 3 tiêu chí nhanh, hiệu quả và linh hoạt, Flutter ra đời và trở thành đối trọng với React Native. Hiện nay, Flutter đang dần là xu thế mới trong lập trình phần mềm.

Một số đặc điểm nổi bật của Flutter:

- Là 1 react framework.

- Sử dụng ngôn ngữ lập trình Dart, là 1 ngôn ngữ đơn giản và dễ học.

- Phát triển ứng dụng nhanh qua tính năng hot reload.

- Giao diện ứng dụng được build bởi Flutter có hiệu năng cực cao hơn hẳn các framework khác như React native.

- Xây dựng bộ widget phù hợp với nguyên tắc của Material Design và Curpotine, giúp các nhà phát triển có thể tiết kiệm thời gian trong việc dựng UI.

Các bạn có thể đọc thêm về Flutter trên các trang khác, ở đây mình chỉ giới thiệu sơ qua vậy thôi!

> Vì mình là một lập trình viên iOS nên mình sẽ hướng dẫn các bạn sử dụng Flutter để lập trình ứng dụng di động.



## 3. Các công cụ cần chuẩn bị để lập trình với Flutter

Đầu tiên, bạn cần [tải và cài đặt Flutter](https://docs.flutter.dev/get-started/install?gclid=CjwKCAjw4ayUBhA4EiwATWyBropvvQHmsTXV6sIBEbby-GVADpdzUWnhLzzpmoZ9I2ZItcKNwsldkxoCj6wQAvD_BwE&gclsrc=aw.ds).

Sau đó là IDE để lập trình Flutter. Ở đây, bạn có thể sử dụng [Android Studio](https://developer.android.com/studio) hoặc là [Visual Studio Code](https://code.visualstudio.com/download).

Khi lập trình ứng dụng di động thì bạn cần có simulator / emulator để có thể build code lên và xem giao diện của ứng dụng bạn vừa lập trình hiển thị ra sao. Bạn cũng có thể lựa chọn cách build test lên device thật để tiết kiệm được bộ nhớ nhưng theo mình thì dù sao các bạn cũng phải cần có native IDE (Android Studio cho android / XCode cho iOS) nên mình nghĩ tốt nhất là tận dụng luôn simulator / emulator của native IDE.

> Vì sao cần phải có native IDE? Đó là vì Flutter là 1 react framework và đôi khi các bạn sẽ gặp phải trường hợp cần debug hoặc cần sử dụng đến các native API. Tất nhiên là có các package để hỗ trợ các bạn nhưng tin mình đi, các pakage đó cũng có bug và đôi khi thay vì khùng điên fix nó hoặc chờ dev của họ fix thì các bạn nên tự code ra hơn. Vừa học hỏi được mà vừa dễ maintain.

> Để sử dụng native API trên Flutter thì mời các bạn đọc qua [bài viết này]() của mình.

Cách cài native IDE:

- Android Studio: bạn download về và cài đặt qua [đây](https://developer.android.com/studio).

- Xcode: khá chua là XCode chỉ có thể down được từ App Store hoặc [trang download của Apple](https://developer.apple.com/download/all/) và việc này đòi hỏi bạn phải có 1 cái máy chạy hệ điều hành MacOS (sử dụng Macbook chính chủ hoặc dùng Hackintosh trên các dòng máy khác) hoặc apple id.



## 4. Quá trình tự học của mình

Mình sẽ tóm gọn và chia nhóm các nội dung trong quá trình học ở lược đồ dưới đây:

![process](https://github.com/vanle57/flutter-self-study-process/blob/main/images/Self-study%20Flutter%20proccess.png)

### 1. Dart:

Bắt đầu từ một người đã có nền tảng về lập trình mobile (cụ thể là iOS) trước đó, việc tự học Flutter sẽ khá dễ dàng hơn cho mình so với những bạn chưa có nền tảng này. Vì Flutter là framework được viết trên ngôn ngữ lập trình Dart nên việc đầu tiên và trước nhất bạn cần là **học về cú pháp của Dar**t. Một số nguồn tài liệu mình sử dụng để
tự học Dart:

- [Cú pháp cơ bản lập trình Dart](https://xuanthulab.net/cu-phap-co-ban-lap-trinh-dart.html).

- [Các hướng dẫn lập trình Dart](https://openplanning.net/12809/dart): bạn nên học từ bài 11 đến bài 22 trong list này.

- [Học nhanh ngôn ngữ Dart (Flutter) nhờ ngôn ngữ Kotlin - Viblo](https://viblo.asia/s/hoc-nhanh-ngon-ngu-dart-flutter-nho-ngon-ngu-kotlin-dbZN76DvlYM): cái này rất có lợi cho những bạn đã biết về Kotlin và nó cũng khá tương tự Swift nên những bạn có
  kinh nghiệm Swift cũng dễ nắm bắt.

- Nếu trình độ tiếng Anh của bạn cũng khá ổn thì sử dụng tài liệu chính chủ này: [Dart cheatsheet codelab | Dart](https://dart.dev/codelabs/dart-cheatsheet).

**** Trình tự cho các bạn tự học Dart:***



### 2. Flutter:

#### 2.1. UI:

##### 2.1.1. UI Widget:

Sau khi đã nắm được những cú pháp căn bản của Dart, các bạn có thể chuyển qua **học về 1 số Widget cơ bản của Flutter.** Một số nguồn tài liệu mình sử dụng để tự học Widget của Flutter:

- [Introduction to widgets | Flutter.](https://docs.flutter.dev/development/ui/widgets-intro)

- [Các hướng dẫn lập trình Flutter](https://openplanning.net/12815/flutter?fbclid=IwAR1taonqqRyaSuqIJ_PHRlkOFal7R9YCPJ1lk-Hk7LyA6FOjft73MNm_bIM): bạn nên học các bài 16, 25 -> 32, 35 36, 38 -> 43, 1 vài bài trong số những bài còn lại thì liên quan đến layout nhiều hơn nên mình để học phía sau, còn vài widget trong list thì không dùng thường xuyên lắm nên các bạn muốn thì có thể tìm hiểu thêm cho biết.

> Layout là gì? Hiểu nôm na đó sẽ là cách bạn sắp xếp các widget trên màn hình và vị trí của chúng. Ví dụ như là chúng nằm giữa màn hình, khoảng cách giữa chúng là bao nhiêu, khoảng cách của 1 widget đối với màn hình, các widget sắp xếp theo chiều dọc hay theo chiều ngang… vân vân và mây mây…

**** Tip của mình:*** Trong khi học đến bài nào thì mình hay research tiếp về loại widget đó trên trang [material library](https://api.flutter.dev/flutter/material/material-library.html) của flutter để đọc thêm về nó. Còn nếu các bạn muốn nhanh thì có thể vừa thực hành vừa học. Chút nữa mình sẽ cung cấp cho các bạn nguồn source tutorial để các bạn có thể thực hành.



##### 2.1.2. Layout:

Okay! Vậy là bạn đã đi được 1/2 của chặng đường học UI. Bây giờ, mình sẽ tiếp tục học những Widget có liên quan đến layout của bạn. Một số các Widget đó là:

- [Center](https://openplanning.net/13105/flutter-center)

- [Align](https://openplanning.net/13109/flutter-align)

- [Row](https://openplanning.net/13103/flutter-row)

- [Column](https://openplanning.net/13101/flutter-column)

- [Stack](https://openplanning.net/13107/flutter-stack)

- [IndexedStack](https://openplanning.net/13227/flutter-indexedstack)

- [EdgeInsets](https://openplanning.net/12891/flutter-edgeinsetsgeometry)

- [Alignment](https://openplanning.net/13219/flutter-alignment)

- [Positioned](https://openplanning.net/13225/flutter-positioned)

- [Expanded](https://openplanning.net/13117/flutter-expanded)

- [Spacer](https://openplanning.net/12935/flutter-spacer)

> Và 1 số thuộc tính có trong các Widget như width, height...



Tới đây thì các bạn đã có thể thực hành rồi cho quen cách làm việc với các Widget trong Flutter và nắm rõ 1 số Widget cơ bản. Một số bài tập để các bạn thực hành:

- Flutter Layout: [Layouts in Flutter | Flutter](https://docs.flutter.dev/development/ui/layout)

-  WhatsApp: [GitHub - iampawan/FlutterWhatsAppClone: Building a WhatsApp Clone in Flutter.](https://github.com/iampawan/FlutterWhatsAppClone)

- Instargram: [GitHub - iampawan/Flutter-Instagram-UI-Clone: Instagram Ui Clone made using Flutter.](https://github.com/iampawan/Flutter-Instagram-UI-Clone)

- Hoặc bạn có thể kiếm 1 số UI đẹp đẹp trên [Pinterest](https://www.pinterest.com/search/pins/?q=mobile%20design%20UI&rs=typed&term_meta%5b%5d=mobile%7Ctyped&term_meta%5b%5d=design%7Ctyped&term_meta%5b%5d=UI%7Ctyped) để follow và làm theo

**** Lưu ý:***

- Khi nhìn vào UI mà bạn khó xác định được đó là loại Widget nào thì có thể tham khảo [Flutter Gallery](https://gallery.flutter.dev/#/).

- Đối với những bạn dev từ nền tảng khác sang (Android, iOS, web…) thì đọc thêm [doc của Flutter cho lập trình viên từng nền tảng](https://docs.flutter.dev/get-started/flutter-for/android-devs), các bạn sẽ cảm thấy dễ tiếp cận hơn đấy!



#### 2.2. Navigation & Router:

Đối với những bạn có kiến thức về lập trình mobile, chắc hẳn đã quá quen với 2 khái niệm này. Hiểu đơn giản nôm na đây chính là điều hướng giữa các màn hình. Trong 1 ứng dụng thì chắc chắn không thể nào thiếu việc này (trừ khi ứng dụng của bạn chỉ có 1 màn hình duy nhất). Mình lấy ví dụ như khi bạn vào gặp màn hình Login và login xong thì vào Home, quá trình chuyển đổi giữa màn hình Login và màn hình Home chính là **Navigation** (hay còn gọi là điều hướng).

Các bạn có thể tham khảo 1 số nguồn tài liệu sau về các kỹ thuật điều hướng trong Flutter:

- [Toàn tập Flutter navigation](https://viblo.asia/p/toan-tap-flutter-navigation-Az45bDwVZxY)

- [Navigation và Routing trong Flutter](https://openplanning.net/13151/flutter-navigation-and-routing)

- Chính chủ: [Navigation and routing | Flutter](https://docs.flutter.dev/development/ui/navigation)



#### 2.3. State Management:

Trước tiên, bạn phải biết trạng thái (State) là gì. Các bạn nên đọc qua [bài viết này](https://cafedev.vn/tu-hoc-flutter-tim-hieu-ve-cach-quan-ly-statetrang-thai-trong-flutter/). Nếu bạn đủ quyết tâm và muốn đào sâu kiến thức thì có thể đọc [loạt bài viết chính chủ này](https://docs.flutter.dev/development/data-and-backend/state-mgmt/intro). Tuy nhiên, cá nhân mình thì thấy thêm để tránh mất thời gian và gây nản chí vì đọc không hiểu, ban đầu bạn chỉ cần nắm khái niệm cơ bản và hiểu được cách nó hoạt động, còn những gì sâu xa thì qua quá trình làm, các bạn đã đủ vững rồi thì có thể tiếp tục đào sâu.

Sau đó sẽ đến [list state management này](https://docs.flutter.dev/development/data-and-backend/state-mgmt/options). Trong list này thì:

- [setState](https://docs.flutter.dev/development/data-and-backend/state-mgmt/options#setstate): chính chủ Flutter, cơ bản của cơ bản trong việc quản lý state nên cần nắm rõ.

- [InheritedWidget & InheritedModel](https://docs.flutter.dev/development/data-and-backend/state-mgmt/options#inheritedwidget--inheritedmodel): cũng chính chủ Flutter và là nền tảng nên cũng nên tìm hiểu qua.

- [Bloc](https://docs.flutter.dev/development/data-and-backend/state-mgmt/options#bloc--rx): 1 pattern ngoài, hay được áp dụng nhiều nhất trong Flutter.

- [Redux](https://docs.flutter.dev/development/data-and-backend/state-mgmt/options#redux): pattern này chủ yếu áp dụng cho React Native, những dev chuyển từ React Native qua sẽ cảm thấy rất quen thuộc.

Tới đây rồi thì các bạn đã đủ công cụ để làm 1 cái app nho nhỏ rồi. Còn những thứ như network thì các bạn có thể tìm hiểu tiếp trong quá trình thực hành vì thực ra Flutter có rất nhiều package hỗ trợ cho các bạn trong việc request api.

Một số source app bạn có thể thực hành:

- [Bloc - Todos app](https://bloclibrary.dev/#/fluttertodostutorial)

- [Bloc - Devfest app](https://github.com/iampawan/GDG-DevFest-App)



## 5. Tạm kết



