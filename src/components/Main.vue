<template>
  <div class="wrapper" id="main_page">
    <header>
      <div class="login_wrapper">
        <div class="socials">
          <ul>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
          </ul>
        </div>
        <div class="login">
          <div class="login_nav">
            <div class="user_enter">ВХОД</div>
            <div class="user_registration">РЕГИСТРАЦИЯ</div>
            <div class="lang">
              <span class="lang_name ENG">ENG</span><span class="lang_arrow_zone"><span class="lang_arrow"></span></span>
              <span class="lang_name RU">RU</span>
              <span class="lang_name UKR">UKR</span>
            </div>
          </div>
        </div>
        <div class="menu">
          <ul class="navigation">
            <li><a href="#">ГЛАВНАЯ</a></li>
            <li><a href="#">ВОЗМОЖНОСТИ</a></li>
            <li><a href="#">ЦЕНЫ</a></li>
            <li><a href="#">РАЗРАБОТЧИКАМ</a></li>
          </ul>
        </div>
      </div>
      <div class="header_container">
        <div class="header_main">
          <a href="#"><div class="logo"></div></a>
          <nav>
            <ul class="navigation">
              <li><a href="#">ГЛАВНАЯ</a></li>
              <li><a href="#">ВОЗМОЖНОСТИ</a></li>
              <li><a href="#">ЦЕНЫ</a></li>
              <li><a href="#">РАЗРАБОТЧИКАМ</a></li>
            </ul>
            <div class="socials">
              <ul>
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>
                <li><a href="#"></a></li>
              </ul>
            </div>
          </nav>
          <div class="header_main_text">
            <h1>ОТПРАВИТЬ ФАКС?</h1>
            <h2>ЕЩЕ НИКОГДА НЕ БЫЛО ТАК ПРОСТО!</h2>
            <p>
              Больше не нужна телефонная линия, все можно
              сделать даже со смартфона.
            </p>
            <button class="registration"><span class="reg">ЗАРЕГИСТРИРОВАТЬСЯ !</span></button>
          </div>
        </div>
        <div class="map"></div>
        <div class="graphic"></div>
      </div>
    </header>
    <main>
      <h1>КАК ОТПРАВИТЬ ФАКС?</h1>
      <h4>Нужно лишь несколько простых действий</h4>
      <ul class="actions">
        <li class="step">
          <div class="step_img img1"></div>
          <h3 class="step_text1">
            ЗАРЕГИСТРИРОВАТЬСЯ И ВОЙТИ
          </h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Sed eleifend ac et bibendum.
          </p>
        </li>
        <li class="arrow"></li>
        <li class="step">
          <div class="step_img img2"></div>
          <h3 class="step_text2">
            ЗАГРУЗИТЬ ДОКУМЕНТ И ВВЕСТИ НОМЕР
          </h3>
          <p>
            Lorem ipsum dolor sit amet, consectetur lit. Sed eleifend
            ac lectus et bibendum.
          </p>
        </li>
        <li class="arrow"></li>
        <li class="step">
          <div class="step_img img3"></div>
          <h3 class="step_text3">
            ПОДОЖДАТЬ И ПОСМОТРЕТЬ
          </h3>
          <p>
            Lorem ng elit. Sed es et bleifend
            bibendum. Lorem ng elit. Sed es et bleifend bibendum.
          </p>
        </li>
        <li class="arrow"></li>
        <li class="step">
          <div class="step_img img4"></div>
          <h3 class="step_text4">
            ЗАБЫТЬ О<br>
            ФАКС&ndash;МАШИНЕ
          </h3>
          <p>
            Lorgfbfbfdfvibendum.<br>
            Donec sed elit at erat placerat lacidv  nia.
          </p>
        </li>
      </ul>

    </main>
    <div class="offer">
      <div class="section"></div>
      <div class="offer_content">
        <div class="ourOffer">
          <h4><span class="megaphone"></span><span class="megaphone_text">Что мы предлагаем?</span></h4>
          <h1>НАШЕ ПРЕДЛОЖЕНИЕ</h1>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Sed eleifend ac lectus et bibendum.<span class="delete_text2"> Donec sed elit at erat
            placerat lacinia. Maecenas mattis purus id libero sagittis,
            in tempor lacus ornare. Suspendisse potenti. Vestibulum
            eleifend</span><span class="delete_text"> diam in nibh bibendum, placerat euismod leo blandit.
            Nunc elementum justo mauris, sit amet aliquam arcu laoreet in.
            Maecenas in dignissim diam.</span>
          </p>
          <button class="registration"><span class="reg">ЗАРЕГИСТРИРОВАТЬСЯ !</span></button>
        </div>
        <div class="interactiveBlock">
          <div class="blocks_wrapper">
            <ul class="blocks_container">
              <li class="blocks block11 active" :class="{ active: isActive }" @click="active"></li>
              <li class="blocks block22" :class="{ active: isActive }" @click="active"></li>
              <li class="blocks block33" :class="{ active: isActive }" @click="active"></li>
              <li class="blocks block44" :class="{ active: isActive }" @click="active"></li>
              <li class="blocks block55" :class="{ active: isActive }" @click="active"></li>
              <li class="blocks block66" :class="{ active: isActive }" @click="active"></li>
            </ul>
            <div class="blocks_content active" :class="{ active: isActive }">
              <h3>
                Работа 24⁄7
              </h3>
              <p>
                Сервис полностью автоматизирован и работает 24 часа 7 дней в неделю
              </p>
            </div>
            <div class="blocks_content" :class="{ active: isActive }">
              <h3>
                Шифрование документов
              </h3>
              <p>
                Ваши документы не могут быть прочитаны посторонними
              </p>
            </div>
            <div class="blocks_content" :class="{ active: isActive }">
              <h3>
                Многоканальные номера
              </h3>
              <p>
                Несколько абонентов могут дозвониться по одному номеру одновременно
              </p>
            </div>
            <div class="blocks_content" :class="{ active: isActive }">
              <h3>
                Оборудование больше не нужно
              </h3>
              <p>
                Избавляем от телефонных линий, операторов связи и факсовой бумаги
              </p>
            </div>
            <div class="blocks_content" :class="{ active: isActive }">
              <h3>
                Ваши документы всегда под рукой
              </h3>
              <p>
                Все принятые документы находятся в вашем email ящике или в личном кабинете и доступны ото всюду
              </p>
            </div>
            <div class="blocks_content" :class="{ active: isActive }">
              <h3>
                Документы имеют юридическую силу
              </h3>
              <p>
                Документы принятые нашим сервисом имеют силу бумажного факс-документа
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <div class="footer_content">
        <div class="footer_entries">
          <a href="#"><div class="footer_logo"></div></a>
          <div class="lang">
            <span class="lang_name ENG">ENG</span><span class="lang_arrow_zone"><span class="lang_arrow"></span></span>
            <span class="lang_name RU">RU</span>
            <span class="lang_name UKR">UKR</span>
          </div>
          <div class="lang_place"></div>
          <a class="footer_copyright" href="#">копирайт</a>
          <a class="footer_policy" href="#">Политика безопасности</a>
          <a class="footer_rules" href="#">Правила пользования</a>
        </div>
        <div class="socials">
          <ul>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
            <li><a href="#"></a></li>
          </ul>
        </div>
      </div>
    </footer>
    <div class="footer_down">
      <a class="footer_copyright" href="#">ByFax копирайт</a>
      <div class="socials">
        <ul>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
          <li><a href="#"></a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
  import '../assets/style/mainStyle.scss'
export default {
  name: 'Main',
  data: () => ({
    isActive: false
  }),
  methods: {
    active(event) {
      const blocks = document.getElementsByClassName ("blocks");
      const blocksContent = document.querySelectorAll(".blocks_content");
      for (let i=0; i<blocks.length; i++) {
        blocks[i].className = `blocks block${i+1}${i+1}`;
        blocksContent[i].className = "blocks_content";
      }
      event.target.className += ' active';
      let num = event.target.className.split('');
      let index = +num.slice(12,13)
      blocksContent[index-1].className += ' active';
    }
  }
}
</script>

