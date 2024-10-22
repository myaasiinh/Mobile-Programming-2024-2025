# Mobile-Programming-2024-2025

# Software Engineering Concepts

Berikut adalah teori singkat dari konsep-konsep software engineering yang disebutkan:

## 1. Breakdown Task
Proses memecah fitur atau tugas besar menjadi unit-unit lebih kecil dan terkelola. Setiap unit memiliki tanggung jawab yang jelas, memudahkan pengembangan, pengujian, dan pemeliharaan.

Contoh :

dari gambar dimana sesuai struktur file ini, petakan perfile algoritma dalam penjelasan bahasa indonesia cara codenya : 

lib :

  ```
core:
    - global_component:
      - Typography.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - ButtonComponent.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - ProgressBarComponent.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - AvatarComponent.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - NetworkImageLoader.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
    - config :
      - main_app.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
    - utils :
      - route_utils.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
    - constants :
      - string -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - color -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - images -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya


  data:
      course:
      - modelresponses:
        - CourseResponse.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - dummy:
        - DummyCourses.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      profile:
      - modelresponses:
        - ProfileResponse.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - dummy:
        - DummyProfile.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      quizez:
      - modelresponses:
        - QuizResponse.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - dummy:
        - DummyQuiz.dart    -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya



  features:
    course_display:
      - screen:
        - HomeScreen.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - widgets:
        - CourseCardWidget.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
        - ContinueLearningWidget.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
        - AvatarWidget.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - controller:
        - HomeController.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
    quiz_interface:
      - screen:
        - QuizScreen.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - widgets:
        - QuizCardWidget.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
        - AnswerOptionWidget.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
        - ProgressBarComponent.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - controller:
        - QuizController.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya 		
    onboarding:
      - screen:
        - WelcomeScreen.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - widgets:
        - WelcomeIllustrationWidget.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
        - GetStartedButtonWidget.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - controller:
        - WelcomeController.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya		
      profile_management:
      - screen:
        - ProfileScreen.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - widgets:
        - AvatarWidget.dart  -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
        - ProfileDetailsWidget.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
      - controller:
        - ProfileController.dart -> buatkan step deskripsi cara code sesuai digambar itu dimana :
				- 
				-
				- dan seterusnya
```

## 2. TDD (Test-Driven Development)
Metodologi pengembangan perangkat lunak di mana tes ditulis sebelum kode implementasi. Tujuannya adalah untuk memastikan setiap fungsi berjalan dengan benar dan sesuai spesifikasi sebelum diintegrasikan ke sistem.

## 3. MVVM (Model-View-ViewModel)
Pola arsitektur yang memisahkan logika bisnis (Model), tampilan antarmuka (View), dan pengelolaan data (ViewModel) untuk meningkatkan keterpisahan dan keterkelolaan kode.

Contoh :

lib :

      core:
        - global_component:
          - Typography.dart 
          - ButtonComponent.dart 
          - ProgressBarComponent.dart 
          - AvatarComponent.dart 
          - NetworkImageLoader.dart 
        - config :
          - main_app.dart
        - utils :
          - route_utils.dart
        - constants :
          - string
          - color
          - images


      data:
          course:
          - modelresponses:
            - CourseResponse.dart 
          - dummy:
            - DummyCourses.dart 
          profile:
          - modelresponses:
            - ProfileResponse.dart 
          - dummy:
            - DummyProfile.dart 
          quizez:
          - modelresponses:
            - QuizResponse.dart 
          - dummy:
            - DummyQuiz.dart    



      features:
        course_display:
          - screen:
            - HomeScreen.dart
          - widgets:
            - CourseCardWidget.dart
            - ContinueLearningWidget.dart
            - AvatarWidget.dart
          - controller:
            - HomeController.dart 
        quiz_interface:
          - screen:
            - QuizScreen.dart 
          - widgets:
            - QuizCardWidget.dart 
            - AnswerOptionWidget.dart 
            - ProgressBarComponent.dart 
          - controller:
            - QuizController.dart 		
        onboarding:
          - screen:
            - WelcomeScreen.dart 
          - widgets:
            - WelcomeIllustrationWidget.dart
            - GetStartedButtonWidget.dart 
          - controller:
            - WelcomeController.dart		
          profile_management:
          - screen:
            - ProfileScreen.dart 
          - widgets:
            - AvatarWidget.dart 
            - ProfileDetailsWidget.dart 
          - controller:
            - ProfileController.dart 


	


## 4. Clean Code, Maintainable, Readable, Scalable
Prinsip-prinsip menulis kode yang bersih dan rapi agar mudah dipelihara, dibaca, serta dapat diskalakan. Kode yang terstruktur dengan baik mendukung kemudahan pengembangan di masa depan dan meminimalkan kesalahan.

## 5. Separation of Concern
Prinsip yang menyarankan agar setiap komponen dalam aplikasi memiliki tanggung jawab khusus. Hal ini mendorong modularitas dan keterkelolaan kode, serta memudahkan perbaikan dan pengembangan fitur baru.

## 6. State Management
Teknik pengelolaan status atau kondisi aplikasi yang memungkinkan bagian-bagian berbeda dari aplikasi untuk berbagi dan memperbarui status. State management yang baik memastikan perubahan dalam data atau logika aplikasi segera tercermin dalam tampilan.

## 7. Integrate API
Proses menghubungkan aplikasi dengan layanan eksternal melalui Application Programming Interface (API). Integrasi API memungkinkan aplikasi untuk berinteraksi dengan server atau sistem lain untuk mengirim atau menerima data.

## 8. Layouting
Penataan antarmuka pengguna untuk membuat aplikasi terlihat baik dan responsif di berbagai ukuran layar. Layouting yang baik mempertimbangkan estetika, fungsi, dan pengalaman pengguna.

---



Repository untuk mata kuliah mobile programming dan praktikum bertanya materi dan fixing bug

1. Laptop jadul procesor tdk bs utk emulator utk aktifin virtualisasi [Issue 4](https://github.com/myaasiinh/Mobile-Programming-2024-2025/issues/4)
   
   Solusi : Make crhome gpp, atau lewat hp asli disambungin lewat kabel, aktifin debug usb di mode pengembang, coba cari di internet sesuai merek hp ada tutornya
