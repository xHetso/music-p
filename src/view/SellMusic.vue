<template>
  <div class="container">
    <div class="b h-[700px] object-scale-down rounded-[20px] text-[white]">
      <div class="pt-[100px] px-[200px]">
        <h1 class="font-bold text-[35px] text-center pt-[30px]">
          Beats-ті нарыққа шығару және сату үшін кәсіпкер өндірушілерге арналған
          № 1 платформаға қосылыңыз
        </h1>
        <p class="text-center p-[55px] text-[20px]">
          Air bit сізге табысты музыкалық бизнесті құруға және жанкүйерлер
          базасын арттыруға қалай көмектесетіні туралы көбірек білгіңіз келе ме?
          Төменде атыңызды және электрондық пошта мекенжайыңызды енгізіңіз.
        </p>
      </div>
    </div>

    <div class="bg-black text-white mt-[30px] rounded-[20px]">
      <h1 class="font-bold text-[35px] text-center py-[30px]">Баға белгілеу</h1>
      <div class="flex justify-evenly pt-[25px]">
        <div class="w-[500px]">
          <div class="1 bg-[#6900FF] text-white rounded-t-[15px]">
            <p class="text-center text-[35px] font-bold">Platinum</p>
            <p class="text-center text-[25px]">1600тг</p>
          </div>
          <div class="2 bg-[#0D041F] text-[17px] pb-[30px] rounded-b-[15px]">
            <div class="flex px-[30px] mt-[25px]" v-for="i in data">
              <p class="text-[#6900FF] mr-[15px]">✔</p>
              <p>{{ i }}</p>
            </div>
          </div>
        </div>
        <div class="w-[500px]">
          <div class="1 bg-[#201B21] text-white rounded-t-[15px]">
            <p class="text-center text-[35px] font-bold">Basic</p>
            <p class="text-center text-[25px]">Free</p>
          </div>
          <div class="2 bg-[#0D0D0D] text-[17px] pb-[30px] rounded-b-[15px]">
            <div class="flex px-[30px] mt-[25px]" v-for="i in data1">
              <p class="text-[#6900FF] mr-[15px]">✔</p>
              <p>{{ i }}</p>
            </div>
          </div>
        </div>
      </div>
      <div class="flex justify-around pt-[30px] pb-[30px]">
        <div
          class="bg-[#6900FF] w-[250px] flex items-center rounded-[10px] p-[15px]"
        >
          <div>
            <h1 class="text-[30px] font-bold">$50M+</h1>
            <p class="text-yellow-400 font-bold">Өндірушілер Тапқан</p>
          </div>
          <img class="w-[60px] h-[60px]" src="../assets/money.png" alt="" />
        </div>
        <div
          class="bg-[#6900FF] w-[250px] flex items-center rounded-[10px] p-[15px]"
        >
          <div>
            <h1 class="text-[35px] font-bold">800K+</h1>
            <p class="text-yellow-400 font-bold">Пайдаланушылар</p>
          </div>
          <img class="w-[60px] h-[60px]" src="../assets/user.png" alt="" />
        </div>
        <div
          class="bg-[#6900FF] w-[250px] flex items-center rounded-[10px] p-[15px]"
        >
          <div>
            <h1 class="text-[35px] font-bold">2M+</h1>
            <p class="text-yellow-400 font-bold">Биттер Сатылды</p>
          </div>
          <img class="w-[60px] h-[60px]" src="../assets/bit.png" alt="" />
        </div>
        <div
          class="bg-[#6900FF] w-[250px] flex justify-between items-center rounded-[10px] p-[15px]"
        >
          <div>
            <h1 class="text-[35px] font-bold">100+</h1>
            <p class="text-yellow-400 font-bold">Елдер</p>
          </div>
          <img class="w-[60px] h-[60px]" src="../assets/count.png" alt="" />
        </div>
      </div>
      <h1 class="text-[60px] font-bold text-center py-[30px]">
        Жоғары Ерекшеліктері
      </h1>
      <div class="">
        <div class="bg-[#201B21] h-[20px] w-[100%] rounded-t-[25px]"></div>
        <div class="bg-[#130F14] h-[500px] flex justify-between">
          <div class="w-[450px] p-[30px] mt-[50px]">
            <img src="../assets/h.png" alt="" />
            <p class="text-[#C636AF] font-bold text-[25px]">
              Бірлескен Продюсерлер
            </p>
            <p>
              Өзіңіздің сүйікті продюсерлеріңізбен бірлесіп жұмыс жасаңыз және
              Air bit-те кірістің бөлінуін жазыңыз. Ынтымақтастық сатылған сайын
              біз төлемдердің бөлінуін тіркейміз.
            </p>
          </div>

          <div class="w-[450px] p-[30px] mt-[50px]">
            <img src="../assets/m.png" alt="" />
            <p class="text-[#C636AF] font-bold text-[25px]">
              Дыбыстық Пакеттерді Сатыңыз
            </p>
            <p>
              Сіз жай ғана музыка шығарып қана қоймай, дыбыстар шығарасыз.
              Жинақтарды жасаңыз, оларды есептік жазбаңызға жүктеңіз және
              өнімдеріңізбен одан да үлкен аудиторияға жетіңіз.
            </p>
          </div>

          <div class="w-[450px] p-[30px] mt-[50px]">
            <img src="../assets/i.png" alt="" />
            <p class="text-[#C636AF] font-bold text-[25px]">Интеграциялар</p>
            <p>
              MailChimp және GetResponse сияқты сүйікті тарату тізімінің
              провайдерлерін, Twitter, YouTube және Facebook сияқты әлеуметтік
              медианы және Google Analytics және Facebook Pixel сияқты
              аналитиканы қосыңыз.
            </p>
          </div>
        </div>
      </div>

      <h1 class="text-[60px] font-bold text-center py-[30px]">Пікірлер</h1>
      <div class="flex justify-evenly pb-[50px]">
        <div class="w-[350px] bg-[#098C8C] p-[30px] h-[350px] rounded-[20px]">
          <img
            src="../assets/default@300x.jpg"
            class="w-[60px] h-[60px] rounded-full"
            alt=""
          />
          <p class="my-[10px]">Killa Music</p>
          <p>
            "@airbit-ең жақсы 💯. Клиенттерге ғана емес, сонымен қатар өз
            клиенттеріне, клиенттеріне де әуестенетін клиенттер.”
          </p>
        </div>
        <div class="w-[350px] bg-[#4D2386] p-[30px] h-[350px] rounded-[20px]">
          <img
            src="../assets/tx.jpg"
            class="w-[60px] h-[60px] rounded-full"
            alt=""
          />
          <p>TnTXD</p>
          <p class="my-[10px]">
            "Мен Airbit-Ті 4-5 жылдан бері қолданып келемін [өйткені бұл маған
            адамдарға автоматты түрде бит жіберуге мүмкіндік береді]... мен одан
            да көп орын аламын"
          </p>
        </div>
        <div class="w-[350px] bg-[#831D47] p-[30px] h-[350px] rounded-[20px]">
          <img
            src="../assets/1520580300589ad7f31d05dea77c943f@100x.jpg"
            class="w-[60px] h-[60px] rounded-full"
            alt=""
          />
          <p class="my-[10px]">ToneJonez</p>
          <p>
            "Мен Airbit-ті қолдана бастағанда, мен жылына 5 цифр жасай бастадым.
            Airbit-ті біраз уақыт пайдаланғаннан кейін, ол мені 6 фигураны
            жасайтын жерге жеткізді. Егер Мен Airbit - ті пайдаланбасам, мен
            онша көп ақша таба алмас едім. Бақытымызға орай, Airbit маған
            отбасым үшін қажет ақшаны табуға көмектесті.”
          </p>
        </div>
      </div>
    </div>
    <div class="bg-[#131313] mt-[30px] rounded-[30px]">
      <h1 class="text-[60px] font-bold text-center py-[30px] text-white">
        Жиі Қойылатын Сұрақтар
      </h1>

      <div
        v-for="(item, index) in items"
        :key="index"
        class="accordion"
        :class="{ active: item.active }"
      >
        <div
          class="accordion-header rounded-[15px]"
          @click="toggleAccordion(index)"
        >
          {{ item.title }}
        </div>
        <div class="accordion-body rounded-b-[15px]">{{ item.content }}</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: "Айына $7,99 бағасын қалай алуға болады?",
          content:
            "Бұл баға Жыл сайынғы Platinum жазылымына жазылсаңыз ғана қолжетімді болады. Мұнда жазылыңыз",
          active: false,
        },
        {
          title: "Промо-кредиттерімді не үшін пайдалана аламын?",
          content:
            "Жарнамалық несиелерді пайдалану-бұл біздің нарықтағы суретшілер мен басқа сатып алушылардың алдында өз жетістіктеріңізді көрсетудің тәсілі. Сіз алға жылжытатын соққылар іздеу нәтижелерінің жоғарғы жағында, басты бетімізде және marketplace Explore бетінде көрсетіледі. Бұл үлкен экспозиция.",
          active: false,
        },
        {
          title: "Platinum жазылушысы ретінде не жүктей аламын?",
          content:
            "Сізде шексіз соққыларды, әндерді, дыбыстық бумаларды, өнер туындыларын және жинақтарды жүктеп салу мүмкіндігі бар!",
          active: false,
        },
        {
          title:
            "Жыл сайынғы және ай сайынғы жазылудың қандай артықшылықтары бар?",
          content:
            "Platinum жылдық мүшесі ретінде сіз ай сайынғы жазылушыға қарағанда 60% - ға аз төлейсіз! (Жылдам математика: $19,99 x 12 = v 239,88 және 7 7,99 x 12 = $95,88) сондай-ақ, ай сайынғы төлемдерді жүзеге асыруға байланысты бас ауруы туралы алаңдамаудың қажеті жоқ. Сонымен қатар, Platinum Rewards тек жыл сайынғы жазылушыларға қолжетімді, сондықтан сіз тіркелген сәттен бастап серіктесіміздің барлық марапаттарына лезде қол жеткізе аласыз!",
          active: false,
        },
        {
          title:
            "Мен Өзімнің Жеке Infinity Дүкеніме тегін есептік жазба арқылы кіре аламын ба?",
          content:
            "Тегін пайдаланушы ретінде сіздің beats тек нарықта сатылымға шығады. Жеке Infinity Store дүкеніне өзіңіздің жеке домендік атыңызбен кіру үшін Сіз Platinum мүшесі болуыңыз керек.",
          active: false,
        },
        {
          title:
            "Менің бұл жерде тізімде жоқ сұрағым бар. Бұл сұраққа жауапты қайдан алуға болады?",
          content:
            "Көптеген сұрақтарға Жауаптарды Air bit Қолдау веб-сайтынан мына жерден таба аласыз. Егер сізде әлі де сұрақтарыңыз болса, Біздің Қоғамдастықтың Көмекші қызметкерлеріне хабарласыңыз support@airbit.com немесе оларға осында хабарлаңыз, біз көмектесуге қуаныштымыз!",
          active: false,
        },
      ],
      data: [
        "ЖАҢА: Нарықтағы Сатушы Үшін 0% Комиссия Және Сатып Алушы Үшін Комиссия Алынбайды",
        "ЖАҢА: BandLab арқылы Жаһандық Суретшілер Қауымдастығына кіру",
        "ЖАҢА: YT/Tik Tok сайтында Ең Жақсы Бейнелерді Автоматты түрде жасаңыз және Орналастырыңыз",
        "Infinity Store және HTML5 дүкендері 0% комиссиямен",
        "YouTube Мазмұн ИДЕНТИФИКАТОРЫН Монетизациялауға құқылы",
        "Платина Марапаттары",
        "PayPal Және Несие Карталарын қабылдаңыз (Stripe арқылы)",
        "Жеке Лицензиялар және электрондық Келісімшарттар",
        "Ұсыныстарды Қабылдау",
        "Бірлескен Продюсердің Бөлінуі",
        "Жеңілдіктер Мен Купондар",
        "Google Analytics / Facebook Pixel Интеграциясы",
        "Жоспарланған Шығарылымдар",
        "ЖАҢА: Әлеуметтік Құлпын Ашу Тегін Жүктеулер",
        "Ойнату Тізімдерін, Beat Таспаларын Және Альбомдарын Жасаңыз",
        "Әндерді Сатыңыз",
        "Премиум қолдау",
      ],
      data1: [
        "ЖАҢА: 20 Бит Жүктеп Алыңыз (Тек Нарықта)",
        "ЖАҢА: Нарықтағы Сатушы Үшін 0% Комиссия Және Сатып Алушы Үшін Комиссия Алынбайды",
        "ЖАҢА: BandLab арқылы Жаһандық Суретшілер Қауымдастығына кіру",
        "ЖАҢА: Youtube Және Tik Tok сайттарында Ең Жақсы Бейнелерді Автоматты түрде жасаңыз және Орналастырыңыз",
        "ЖАҢА: Әлеуметтік Құлпын Ашу Тегін Жүктеулер",
      ],
    };
  },
  methods: {
    toggleAccordion(index) {
      this.items.forEach((item, i) => {
        if (index === i) {
          item.active = !item.active;
        } else {
          item.active = false;
        }
      });
    },
  },
};
</script>

<style lang="scss" scoped>
.b {
  background-image: url("https://airbit.com/nuxt/img/landing-pages/sell-beats/cover.jpg");
  width: 100%;
}
.accordion {
  font-size: 25px;
  padding: 15px;
  margin-bottom: 10px;
}
.accordion-header {
  font-weight: bold;
  color: white;
  background-color: #000000;
  padding: 10px;
  cursor: pointer;
}
.accordion-body {
  font-size: 20px;
  color: white;
  background-color: #130f14;
  padding: 10px;
  display: none;
}
.accordion.active .accordion-body {
  display: block;
}
.container {
  margin: 0 auto;
  max-width: 1280px;
}
</style>
