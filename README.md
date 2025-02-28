<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Future Ukraine</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="future-ukr.css">
</head>

<body>

    <header> 

        <nav class="menu">
    
            <div>
    
                <img src="img/logo.png" alt="Logo demchenko-livandovska" width="50px" style="margin-left: 10px;">
    
            </div>
    
            <div> 
    
                <ul class="first_ul">
                    <li class="first_li"><a class="first_a" href="#Start">Вступ</a></li>
                    <li class="first_li"><a class="first_a" href="#Info">Наше бачення</a></li>
                    <li class="first_li"><a class="first_a" href="#End">Підсумки</a></li>
                </ul>
    
            </div>
    
        </nav>
               
    </header>
   
    <section class="navigation_on_foto" >
    
        <h1> Майбутнє України </h1>
  
    </section>

    <main>

      <div>
        <a name="Start"></a>
            <p>
                На сьогоднішній день Україна проживає важкі часи, щодня борячись за свободу та незалежність. З приходом ворога на наші землі, українці втратили: 
                свої домівки, сім’ї, спокій, але не втратили віру. Дякуючи нашим захисникам, які боронять нашу країну, ми маємо можливість навчатися, працювати 
                та планувати майбутнє наскільки це можливо. Адже саме ми власноруч, своїми силами, відбудуємо нашу Батьківщину.  Ця стаття присвячена нашим думкам 
                про майбутнє України, як ми його бачимо, і для того щоб вони втілилися в реальність потрібно вірити в нашу перемогу, в ЗСУ та докладати максимум зусиль.
            </p>

            <p style="text-align: center; font-size: 30px;">
              Слава Україні!    Героям Слава!
            </p>
           
      </div>
    
      <div>
    
          <ul class="slider">
            <li class="item" style="background-image: url('https://kor.ill.in.ua/m/1200x0/2877921.jpeg')"></li>
            <li class="item" style="background-image: url('https://static.ukrinform.com/photos/2024_02/thumb_files/630_360_1708840876-817.jpg')"></li>
            <li class="item" style="background-image: url('https://pravdatutnews.com/sites/default/files/news/2022/06/24/viyna.jpg')"></li>
            <li class="item" style="background-image: url('https://img.pravda.com/images/doc/b/4/b49090c-vij-na--most-dnepr-info-.jpg')"></li>
            <li class="item" style="background-image: url('https://static.ukrinform.com/photos/2023_09/thumb_files/630_360_1694276574-223.jpg')"></li>
          </ul>

          <p style="text-align: center; font-size: 20px; padding: 3px ;">
            Наслідки вторгнення росії
          </p>
    
      </div>

      <div>
            <p style="text-align: center; font-size: 20px;">
                Не дивлячись ні на що, росія не забере у нас силу волі, своду і можливість мріяти та втілювати їх в реальність. Ми вірим що майбутня Україна буде ще красивішою, ще сильнішою і ще розвинітішою
            </p>
      </div>
    
      <div class="container ">
        <a name="Info"></a>
        <div id="hidden6" class="apparent">
  
          <div class="box" onclick="hidden_box(0)">Освіта</div>
          <div class="box" onclick="hidden_box(1)">Наука</div>
          <div class="box" onclick="hidden_box(2)">Медицина</div>
          <div class="box" onclick="hidden_box(3)">Екологія</div>
          <div class="box" onclick="hidden_box(4)">Міжнародні відносини</div>
          <div class="box" onclick="hidden_box(5)">Культура</div>

        </div>

     

      <div id="hidden0" class="apparent hidden">

        <button class="close-btn" onclick="close_box(0)">&times;</button>

        <h2 style="text-align: center; color: #ffffff;font-family: Arial, Helvetica, sans-serif; font-size: 52px;">Освіта</h2>
        <div style="display: flex; align-items: center;">
        <img src="https://osvita.ua/doc/images/news/622/62230/5846-001_i.jpg" id="changingImage" alt="Education"  style="margin-right: 20px; width: 400px; height: auto;">
         <h4 style="color: #ffffff; padding: 10px 35px; font-family: Arial, Helvetica, sans-serif; text-align: justify; font-size: 18px; flex: 1;">
          З початком війни українці навчилися пристосовуватись до складних обставин і знаходити нові рішення для продовження життя. Це стосується і навчання,
           діти побували в різних ситуаціях, таких як дистанційне навчання і навіть офлайн навчання у бомбосховищі під час повітряних тривог. Саме цей досвід 
           допоможе зробити нашу освіту ще більш гнучкішою та ефективнішою. За роки розвинуться нові освітні платформи, які зроблять освіту більш доступнішими. 
           Зявляться нові предмети для кращого розуміння ситуації в теперішньому і майбутньому пов’язані з військовою підготовкою, історію та розвиненням критичного мислення.
            А найголовніше, що з кінцем війни повернуться вчителі, науковці і звичайно ж діти, які зможуть навчати і вчитися на своїй Батьківщині. Можлив в майбутньому Україна 
            стане лідер у Європі за якістю освіти.</h4>
            <script>
              // Масив зображень
              const images = [
                  "https://osvita.ua/doc/images/news/622/62230/5846-001_i.jpg",
                  "https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhrs5xtluDZjx8YTfvK0_KtiW5W115BDKeWagEMBhG0tijDU1cng73Qg2eyi2eHtP7Iz3-4-JmgwIbwGHT-3byTdrAlWJhGiiXRLOdDzhf-WqvJiL6v1gHa5n0c60OjZGVdOBNvbSw3FOc/s1600/yaka-ye-osvita-v-Ukrayini-e1442775044714.jpg",
                  "https://vechirniy.kyiv.ua/uploads/2023/09/17/6506daf1aa498.png"
              ];
          
              let index = 0;
              const imgElement = document.getElementById("changingImage");
          
              setInterval(() => {
                  index = (index + 1) % images.length; // Змінюємо індекс (зациклено)
                  imgElement.style.opacity = "0"; // Плавне зникнення
                  setTimeout(() => {
                      imgElement.src = images[index]; // Змінюємо зображення
                      imgElement.style.opacity = "1"; // Плавна поява
                  }, 5);
              }, 3000); // Зміна кожні 5 секунд
          </script>
        </div>
       
      </div>
      
      <div id="hidden1" class="apparent hidden">

        <button class="close-btn" onclick="close_box(1)">&times;</button>
        <h2 style="text-align: center; color: #ffffff;">Наука</h2>
        <div style="display: flex; align-items: center;">
          <h4 style="color: #ffffff; padding: 10px 35px; font-family: Arial, Helvetica, sans-serif; text-align: justify; font-size: 18px; flex: 1;">
            Наука почне стрімко розвиватися у різних сферах, але при цьому більшу увагу будуть приділяти військовим технологіям, кібербезпеці та медицині.
             Держава та бізнеси почнуть більше інвестувати в наукові дослідження, що надасть можливість молодим науковцям реалізувати їхні ідеї у реальність.</h4>
        <img src="https://www.oin.com.ua/wp-content/uploads/2023/12/55667888.jpg" id="changingImages"alt="Science"  style="margin-right: 20px; width: 400px; height: auto;">
        <script>
          // Масив зображень
    const imagess = [
      "https://indicator.ru/thumb/2250x0/filters:quality(75):no_upscale()/imgs/2019/12/20/09/3705805/14b61a2f3a2b50c95c8fee574a9c55d60235b309.jpg",
        "https://www.oin.com.ua/wp-content/uploads/2023/12/55667888.jpg",
        "https://argumentua.com/sites/default/files/imagecache/Full_tekst_600x/article/1378309622_nauka-i-zhizn.jpg"
    ];

    let indexs = 0; // Початковий індекс
    const imgElements = document.getElementById("changingImages");

    setInterval(() => {
        indexs = (indexs + 1) % imagess.length; // Змінюємо індекс (зациклено)
        imgElement.style.opacity = "0"; // Плавне зникнення
        setTimeout(() => {
            imgElements.src = imagess[indexs]; // Змінюємо зображення
            imgElements.style.opacity = "1"; // Плавна поява
        }, 500); // Час для зміни картинки (500 мс)
    }, 3000); // Зміна кожні 3 секунди
      </script>
        </div>

      </div>

      <div id="hidden2" class="apparent hidden">

        <button class="close-btn" onclick="close_box(2)">&times;</button>
        
        <h2 style="text-align: center; color: #ffffff;">Медицина</h2>
        <div style="display: flex; align-items: center;">
          <img src="https://s.mind.ua/img/forall/a/202305/93.jpg?1633359029" id="changingImagess" alt="Medicine"  style="margin-right: 20px; width: 400px; height: auto;">
          <h4 style="color: #ffffff; padding: 10px 35px; font-family: Arial, Helvetica, sans-serif; text-align: justify; font-size: 18px; flex: 1;">
            Після війни почнуть відкриватися нові реабілітаційні центри, для військових та громадян хто постраждав. Окрім цього медицина розвинеться в сфері протезів та в лікуванні
             військових травм. Незважаючи на важке минуле наша медицина може вийти на новий рівень та стати лідером в виготовлені якісних протезів по всьому світу.</h4>
             <script>
              // Масив зображень
        const imagesss = [
           "https://chemoteka.com.ua/images/2ef40/a8005/3ce6034e801f83.png",
           "https://leader-id.storage.yandexcloud.net/event_photo/234007/615e7dbde34ad533396903.jpg",
            "https://s.mind.ua/img/forall/a/202305/93.jpg?1633359029"
           
        ];
    
        let indexss = 0; // Початковий індекс
        const imgElementss = document.getElementById("changingImagess");
    
        setInterval(() => {
            indexss = (indexss + 1) % imagesss.length; // Змінюємо індекс (зациклено)
            imgElement.style.opacity = "0"; // Плавне зникнення
            setTimeout(() => {
                imgElementss.src = imagesss[indexss]; // Змінюємо зображення
                imgElementss.style.opacity = "1"; // Плавна поява
            }, 500); // Час для зміни картинки (500 мс)
        }, 3000); // Зміна кожні 3 секунди
          </script>
        </div>
    
      </div>

      <div id="hidden3" class="apparent hidden">

        <button class="close-btn" onclick="close_box(3)">&times;</button>
       
        <h2 style="text-align: center; color: #ffffff;">Екологія</h2>
        <div style="display: flex; align-items: center;">
          <h4 style="color: #ffffff; padding: 10px 35px; font-family: Arial, Helvetica, sans-serif; text-align: justify; font-size: 18px; flex: 1;">
            Після війни почнеться масова відбудова країни, адже війна завдала дуже великих збитків навколишньому середовищу. Розпочне свою роботу маштабна 
            програма екологічного відновлення України, до неї буде входити розміновування території, очищення довкілля та відновлення лісів. </h4>
        <img src="https://media.dyvys.info/2024/03/vapnrgshoshh.jpg"  id="changingImagessw" alt="Science"  style="margin-right: 20px; width: 400px; height: auto;">
        <script>
          // Масив зображень
    const imagessss = [
       "https://media.dyvys.info/2024/03/vapnrgshoshh.jpg",
       "https://osvita.ua/doc/images/news/673/67336/1143-001_i.jpg",
        "https://vodacpk.com.ua/wp-content/uploads/2023/11/7174.jpg"
       
    ];

    let indexsss = 0; // Початковий індекс
    const imgElementsss = document.getElementById("changingImagessw");

    setInterval(() => {
        indexsss = (indexsss + 1) % imagessss.length; // Змінюємо індекс (зациклено)
        imgElement.style.opacity = "0"; // Плавне зникнення
        setTimeout(() => {
            imgElementsss.src = imagessss[indexsss]; // Змінюємо зображення
            imgElementsss.style.opacity = "1"; // Плавна поява
        }, 500); // Час для зміни картинки (500 мс)
    }, 3000); // Зміна кожні 3 секунди
      </script>
        </div>

      </div>

      <div id="hidden4" class="apparent hidden">

        <button class="close-btn" onclick="close_box(4)">&times;</button>
       
        <h2 style="text-align: center; color: #ffffff;">Міжнародні відносини</h2>
        <div style="display: flex; align-items: center;">
          <img src="https://politteo.online/wp-content/uploads/2021/06/sistemul-geopolitic.jpg" id="changingImagessws" alt="Medicine"  style="margin-right: 20px; width: 400px; height: auto;">
          <h4 style="color: #ffffff; padding: 10px 35px; font-family: Arial, Helvetica, sans-serif; text-align: justify; font-size: 18px; flex: 1;">
            Завдяки своїй перемозі Україна доведе іншим країнам, що вона є незламною та сильною і завдяки цьому зможе налагодити дружні зв’язки з іншими країнами. Також нам 
            дадуть членство в ЄС та Нато, що надасть гарантію безпеки країни. Військовий досвід України допоможе перебудувати європейську систему безпеки, окрім цього буде 
            розвивати співпрацю зі світом.</h4>
            <script>
              // Масив зображень
              const imagessssw = [
                 "https://politteo.online/wp-content/uploads/2021/06/sistemul-geopolitic.jpg",
                  "https://dteducation.com/images/001816-mezhdunarodnye_otnosheniya.jpg"
              ];
          
              let indexsssw = 0; // Початковий індекс
              const imgElementssss = document.getElementById("changingImagessws");
          
              setInterval(() => {
                  indexsssw = (indexsssw + 1) % imagessssw.length; // Змінюємо індекс (зациклено)
                  imgElementssss.style.opacity = "0"; // Плавне зникнення
                  setTimeout(() => {
                      imgElementssss.src = imagessssw[indexsssw]; // Змінюємо зображення
                      imgElementssss.style.opacity = "1"; // Плавна поява
                  }, 50); // Час для зміни картинки (500 мс)
              }, 3000); // Зміна кожні 3 секунди
          </script>
        </div>
      </div>

      <div id="hidden5" class="apparent hidden">

        <button class="close-btn" onclick="close_box(5)">&times;</button>
       
        <h2 style="text-align: center; color: #ffffff;">Культура</h2>
        <div style="display: flex; align-items: center;">
          <h4 style="color: #ffffff; padding: 10px 35px; font-family: Arial, Helvetica, sans-serif; text-align: justify; font-size: 18px; flex: 1;">
            Наразі українська музика, кіно та література набирають популярність за кордоном. Тому можемо припустити, що після нашої перемоги культура України 
            стане ще більш відомішою по всьому світі, адже співаки, режисери, продюсери і тд будуть надихатися героїчними вчинкам, історіями про сильних духом 
            людей та перемогою України. Окрім цього зруйнована окупантами культурна спадщина буде відновлена і буде можливість створити нові архітектурні споруди 
            сучасного світу. </h4>
        <img src="https://odnb.odessa.ua/img/novini_2020/2952/dlya-anonsa.jpg" id="changingImagesswsh" alt="Science"  style="margin-right: 20px; width: 400px; height: auto;">
        <script>
          // Масив зображень
          const imagesssswh = [
             "https://odnb.odessa.ua/img/novini_2020/2952/dlya-anonsa.jpg",
             "https://www.kissfm.ua/static/img/content/userfiles/images/jefferson-santos-fCEJGBzAkrU-unsplash.jpg",
              "https://library.vn.ua/assets/publilc/news/2020/vystavky/78.jpg"
          ];
      
          let indexssswh = 0; // Початковий індекс
          const imgElementssssh = document.getElementById("changingImagesswsh");
      
          setInterval(() => {
              indexssswh = (indexssswh + 1) % imagesssswh.length; // Змінюємо індекс (зациклено)
              imgElementssssh.style.opacity = "0"; // Плавне зникнення
              setTimeout(() => {
                  imgElementssssh.src = imagesssswh[indexssswh]; // Змінюємо зображення
                  imgElementssssh.style.opacity = "1"; // Плавна поява
              }, 50); // Час для зміни картинки (500 мс)
          }, 3000); // Зміна кожні 3 секунди
      </script>
      </div>
      </div>
        
    </div>


    <script>

      function hidden_box(index) {

        // Ховаємо hidden6
        document.getElementById("hidden6").classList.add("hidden");

        let pages = document.querySelectorAll('.apparent'); // Отримуємо всі контейнери
        pages.forEach(page => page.classList.add('hidden')); // Ховаємо всі

        document.getElementById('hidden' + index).classList.remove('hidden'); // Показуємо потрібний

      }

      function close_box(index) {

        document.getElementById("hidden" + index).classList.add("hidden");
        document.getElementById("hidden6").classList.remove("hidden");

      }


    </script>

       
  </main>

  <footer style="background-color: rgb(0, 0, 0);">

    <!--<h2 style="color: white; text-align: center;">Ми студентки Вінницького національного технічного університету</h2>-->
      
    <div class="aboutas"> <!--цей клас можна буде забрати, АЛЕ НЕ ФАКТ-->
      <a name="End"></a>

      <p style="margin-left: 20px; margin-right: 20px;">
      <br>
        Незважаючи на дану ситуацію в Україні, вона всерівно матиме світле майбутнє. Адже, це не перший раз наша країна переживає 
        важкі часи. Згадайте про численні репресії, голодомори, війни, повстання....
       <p style="margin-left: 20px; margin-right: 20px;"> Україна вистояла тоді і вистоїть зараз. Головне для нас наразі не забувати,
         що ми українці – сильна нація, яка не дозволить чужинцям правити нами та нашими землями. Ми повинні вірити, надіятися та боротися, 
         для того щоб наблизити нашу країну до перемоги.</p> 
       <p style="margin-left: 20px; margin-right: 20px;">  Сподіваємося, що вже зовсім скоро усі українці прокинуться у вільній і незалежній 
        Україні. Всі захисники та захисниці повернуться до своїх родин. І ми усі почнемо відбудовувати незалежну, сильну, процвітаючу та єдину Україну.</p>
       <p style="text-align: center; font-size: 30px;"> Україна понад усе! </p>

     

     <!-- <img src="../future-ukr/img/vntu.png" alt="Вінницький національний технічний університет" width="20%" style=" margin-right: 65px;">-->

    </div>

  </footer>
   

</body>

</html>
