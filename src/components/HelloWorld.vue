<template>
  <v-container2 class="bg-surface-variant">
    <v-row class="mb-12" no-gutters>
      <v-col>
        <v-sheet class="pa-2 ma-2">
          <v-card class="mx-auto" max-width="344" hover elevation="16">
            <v-card-item>
              <v-card-title>
                Щоденник недатований А5, 128 аркушів, клітинка, обкладинка
                баладек зелений
              </v-card-title>
              <v-card-subtitle> Артикул: 241/1 06Б гумка </v-card-subtitle>
            </v-card-item>

            <v-card-text
              ><img
                alt="Vue logo"
                class="logo"
                src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F06B_5209_1974_0.jpg?alt=media&token=6be7226f-0667-48a8-bb31-347eaf73c358"
                width="300"
                height="300"
              />

              Діловий щоденник недатований. Формат 145х202 мм. Кількість
              сторінок 352. Блок кремовий офсет 70г/м2, лінія. Колір капталу та
              лясе - золотий. Мова укр., англ. Перфоровані відривні кутики.
              Форзац - кольорові мапи Європи і України. Обкладинка гнучка,
              штучна шкіра, на гумці.Інформаційний блок містить:-Валюти країн
              світу-Позначення країн та територій в Інтернеті-Правила догляду за
              одягом та знаки на етикетці-Розміри одягу та взуття-Одиниці для
              вимірювання фізичних величин-Офіційні правила тлумачення
              торгівельних термінів міжнародної торгової палати Інкотермс
              2020-Автомобільні коди країни-Часові пояси-Відстані між
              європейськими містами та між обласними центрами України-Довідкові
              телефони-Телефонні коди міст України-Міжнародні телефонні
              коди-Міжнародні штрихові коди.
            </v-card-text>
          </v-card>
          <v-row justify="center">
            <v-dialog width="800">
              <template v-slot:activator="{ props }">
                <v-btn color="primary" v-bind="props" text="Open Dialog">
                </v-btn>
              </template>

              <template v-slot:default="{ isActive }">
                <v-card title="">
                  <v-card-text>
                    <v-card-title>
                      <span class="text-h5"
                        >Для індивідуального тиснення фольгою вам
                        необхідно:</span
                      >
                    </v-card-title>
                    <v-card-text color="red">
                      1. заповнити макет
                      <a
                        href="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0firebase.xlsx?alt=media&token=63c3e144-60e8-4691-b2ae-b48646990171"
                        target="_blank"
                        rel="noopener"
                        >Excel</a
                      >
                      та відправити  для узгодження 
                      <v-dialog width="500">
                        <template v-slot:activator="{ props }">
                          <v-btn color="primary" v-bind="props" text="e-mail">
                          </v-btn>
                        </template>

                        <template v-slot:default="{ isActive }">
                          <v-card title="e-mail">
                            <v-card-text>
                              tamazenko@polygraphist.kiev.ua
                            </v-card-text>

                            <v-card-actions>
                              <v-spacer></v-spacer>

                              <v-btn
                                text="Close"
                                @click="isActive.value = false"
                              ></v-btn>
                            </v-card-actions>
                          </v-card>
                        </template>
                      </v-dialog>
                     
                    </v-card-text>
                    <v-card-text>
                      2. тиснення можливе безбарвне, золотим, червоним та срібним кольором
                    
                    </v-card-text>
                    <v-card-text>
                      3. допустима кількість символів в 1 рядку залежить від
                      обраного формату блокнота
                    </v-card-text>
                    <v-card-text>
                      4. вартість тиснення після узгодження (від 100 грн) +
                      <a
                        href="https://polygraphist.kiev.ua/dlya-bznesu-ta-ofsu/dlov-schodenniki/dlov-schodenniki-nedatovan/schodennik-nedatovaniy-a5-176-arkushv-krem.lnya-obkladinka-shtuchna-shkra-bordoviy-na-gumc/"
                        target="_blank"
                        rel="noopener"
                        color="primary"
                        >ціна блокнота</a
                      >
                    </v-card-text>

                    <v-dialog width="500">
                      <template v-slot:activator="{ props }">
                        <v-btn color="primary" v-bind="props" text="оплата">
                        </v-btn>
                      </template>

                      <template v-slot:default="{ isActive }">
                        <v-card title="Приват банк">
                          <v-card-text> 15545454545878788787 </v-card-text>
                          <v-card-text>
                            у призначенні платежу необхідно вказати фамілію
                            плантника
                          </v-card-text>

                          <v-card-actions>
                            <v-spacer></v-spacer>

                            <v-btn
                              text="Close"
                              @click="isActive.value = false"
                            ></v-btn>
                          </v-card-actions>
                        </v-card>
                      </template>
                    </v-dialog>

                    <v-card-text>
                      5. робота виконується лише після 100% оплати замовлення
                    </v-card-text>
                    <v-sheet class="left">
                      <img
                        alt="Vue logo"
                        class="logo mx-auto"
                        src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F06B_5209_1974_0.jpg?alt=media&token=6be7226f-0667-48a8-bb31-347eaf73c358"
                        width="500"
                        height="500"
                      />
                    </v-sheet>
                  </v-card-text>

                  <v-card-actions>
                    <v-spacer></v-spacer>

                    <v-btn
                      text="Close"
                      @click="isActive.value = false"
                    ></v-btn>
                  </v-card-actions>
                </v-card>
              </template>
            </v-dialog>
          </v-row>
        </v-sheet>
      </v-col>

      <v-col>
        <v-sheet class="pa-2 ma-2">
          <v-card class="mx-auto" max-width="344" hover elevation="16">
            <v-card-item>
              <v-card-title>
                Щоденник недатований А5, 128 аркушів, клітинка, обкладинка
                баладек зелений
              </v-card-title>
              <v-card-subtitle> Артикул: 231 0540 </v-card-subtitle>
            </v-card-item>

            <v-card-text>
              <img
                alt="Vue logo"
                class="logo"
                src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F0540_26105_1911_0.jpg?alt=media&token=beb8b885-cb6f-4fac-a1e9-9451af0bca05"
                width="300"
                height="300"
              />

              Діловий щоденник недатований. Формат 145х202 мм. Кількість
              сторінок 256. Блок білий офсет 70г/м2, клітинка. Колір капталу та
              лясе - білий. Мова укр., англ. Форзац - без друку білий.
              Обкладинка баладек.
            </v-card-text>
          </v-card>
          <v-row justify="center">
            <v-dialog width="800">
              <template v-slot:activator="{ props }">
                <v-btn color="primary" v-bind="props" text="Open Dialog">
                </v-btn>
              </template>

              <template v-slot:default="{ isActive }">
                <v-card title="Dialog">
                  <v-card-text>
                    <v-card-title>
                      <span class="text-h5"
                        >Для індивідуального тиснення фольгою вам
                        необхідно:</span
                      >
                    </v-card-title>
                    <v-card-text color="red">
                      1. заповнити макет
                      <a
                        href="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0firebase.xlsx?alt=media&token=63c3e144-60e8-4691-b2ae-b48646990171"
                        target="_blank"
                        rel="noopener"
                        >Excel</a
                      >
                      та відправити за адресою
                      <a href="" target="_blank" rel="noopener"
                        >tamazenko@polygraphist.kiev.ua</a
                      >
                      для узгодження
                    </v-card-text>
                    <v-card-text>
                      2. тиснення можливе безбарвне, золотим, червоним, срібним
                      та білим кольором
                    </v-card-text>
                    <v-card-text>
                      3. допустима кількість символів в 1 рядку залежить від
                      обраного формату блокнота
                    </v-card-text>
                    <v-card-text>
                      4. вартість тиснення після узгодження (від 100 грн) + ціна
                      блокнота
                    </v-card-text>

                    <v-dialog width="500">
                      <template v-slot:activator="{ props }">
                        <v-btn color="primary" v-bind="props" text="оплата">
                        </v-btn>
                      </template>

                      <template v-slot:default="{ isActive }">
                        <v-card title="Приват банк">
                          <v-card-text> 15545454545878788787 </v-card-text>
                          <v-card-text>
                            у призначенні платежу необхідно вказати фамілію
                            плантника
                          </v-card-text>

                          <v-card-actions>
                            <v-spacer></v-spacer>

                            <v-btn
                              text="Close"
                              @click="isActive.value = false"
                            ></v-btn>
                          </v-card-actions>
                        </v-card>
                      </template>
                    </v-dialog>

                    <v-card-text>
                      5. робота виконується лише після 100% оплати замовлення
                    </v-card-text>
                    <v-sheet class="left">
                      <img
                        alt="Vue logo"
                        class="logo mx-auto"
                        src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F0540_26105_1911_0.jpg?alt=media&token=beb8b885-cb6f-4fac-a1e9-9451af0bca05"
                        width="500"
                        height="500"
                      />
                    </v-sheet>
                  </v-card-text>

                  <v-card-actions>
                    <v-spacer></v-spacer>

                    <v-btn
                      text="Close Dialog"
                      @click="isActive.value = false"
                    ></v-btn>
                  </v-card-actions>
                </v-card>
              </template>
            </v-dialog>
          </v-row>
        </v-sheet>
      </v-col>

      <v-col>
        <v-sheet class="pa-2 ma-2">
          <v-card class="mx-auto" max-width="344" hover elevation="16">
            <v-card-item>
              <v-card-title>
                Щоденник недатований А5, 160 аркушів, клітинка, обкладинка
                баладек синій, тисн "Ромби"
              </v-card-title>
              <v-card-subtitle> Артикул: 239 1250 Ромби </v-card-subtitle>
            </v-card-item>

            <v-card-text>
              <img
                alt="Vue logo"
                class="logo"
                src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F239%201250%20%D0%A0%D0%BE%D0%BC%D0%B1%D0%B8.jpg?alt=media&token=489603d5-0b32-427a-ae0c-931912e4bd53"
                width="300"
                height="300"
              />

              Діловий щоденник недатований. Формат 145х202 мм. Кількість
              сторінок 256. Блок білий офсет 70г/м2, клітинка. Колір капталу та
              лясе - білий. Мова укр., англ. Форзац - без друку білий.
              Обкладинка баладек.
            </v-card-text>
          </v-card>

          <v-row justify="center">
            <v-dialog width="800">
              <template v-slot:activator="{ props }">
                <v-btn color="primary" v-bind="props" text="Open Dialog">
                </v-btn>
              </template>

              <template v-slot:default="{ isActive }">
                <v-card title="Dialog">
                  <v-card-text>
                    <v-card-title>
                      <span class="text-h5"
                        >Для індивідуального тиснення фольгою вам
                        необхідно:</span
                      >
                    </v-card-title>
                    <v-card-text color="red">
                      1. заповнити макет
                      <a
                        href="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0firebase.xlsx?alt=media&token=63c3e144-60e8-4691-b2ae-b48646990171"
                        target="_blank"
                        rel="noopener"
                        >Excel</a
                      >
                      та відправити за адресою
                      <a href="" target="_blank" rel="noopener"
                        >tamazenko@polygraphist.kiev.ua</a
                      >
                    </v-card-text>
                    <v-card-text>
                      2. тиснення можливе безбарвне, золотим, червоним, срібним
                      та білим кольором
                    </v-card-text>
                    <v-card-text>
                      3. допустима кількість символів в 1 рядку залежить від
                      обраного формату блокнота
                    </v-card-text>
                    <v-card-text>
                      4. вартість тиснення від 100 грн + ціна блокнота
                    </v-card-text>
                    <v-card-text>
                      5. робота виконується лише після 100% оплати замовлення
                    </v-card-text>
                    <v-sheet class="left">
                      <img
                        alt="Vue logo"
                        class="logo mx-auto"
                        src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F239%201250%20%D0%A0%D0%BE%D0%BC%D0%B1%D0%B8.jpg?alt=media&token=489603d5-0b32-427a-ae0c-931912e4bd53"
                        width="500"
                        height="500"
                      />
                    </v-sheet>
                  </v-card-text>

                  <v-card-actions>
                    <v-spacer></v-spacer>

                    <v-btn
                      text="Close Dialog"
                      @click="isActive.value = false"
                    ></v-btn>
                  </v-card-actions>
                </v-card>
              </template>
            </v-dialog>
          </v-row>
        </v-sheet>
      </v-col>

      <v-col>
        <v-sheet class="pa-2 ma-2">
          <v-card class="mx-auto" max-width="344" elevation="16" hover>
            <v-card-item>
              <v-card-title>
                Щоденник недатований А5, 176 аркушів, лінія, обкладинка штучна
                шкіра, чорний
              </v-card-title>
              <v-card-subtitle> Артикул: 241 2110 </v-card-subtitle>
            </v-card-item>

            <v-card-text>
              <img
                alt="Vue logo"
                class="logo"
                src="https://polygraphist.kiev.ua/images/detailed/8482/2110_5210_s_b_1964_0.jpg"
                width="300"
                height="300"
              />

              Діловий щоденник недатований. Формат 145х202 мм. Кількість
              сторінок 352. Блок білий офсет 70г/м2. Колір капталу та лясе -
              білий. Мова укр., англ. Форзац - кольорові мапи України, Європи.
              Матеріал обкладинки штучна шкіра. Інформаційний блок
              містить:-Валюти країн світу-Позначення країн та територій в
              Інтернеті-Правила догляду за одягом та знаки на етикетці-Розміри
              одягу та взуття-Одиниці для вимірювання фізичних величин-Офіційні
              правила тлумачення торгівельних термінів міжнародної торгової
              палати Інкотермс 2020-Автомобільні коди країни-Часові
              пояси-Відстані між європейськими містами та між обласними центрами
              України-Довідкові телефони-Телефонні коди міст України-Міжнародні
              телефонні коди-Міжнародні штрихові коди
            </v-card-text>
          </v-card>

          <v-row justify="center">
            <v-dialog width="800">
              <template v-slot:activator="{ props }">
                <v-btn color="primary" v-bind="props" text="Open Dialog">
                </v-btn>
              </template>

              <template v-slot:default="{ isActive }">
                <v-card title="Dialog">
                  <v-card-text>
                    <v-card-title>
                      <span class="text-h5"
                        >Для індивідуального тиснення фольгою вам
                        необхідно:</span
                      >
                    </v-card-title>
                    <v-card-text color="red">
                      1. заповнити макет
                      <a
                        href="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0firebase.xlsx?alt=media&token=63c3e144-60e8-4691-b2ae-b48646990171"
                        target="_blank"
                        rel="noopener"
                        >Excel</a
                      >
                      та відправити за адресою
                      <a href="" target="_blank" rel="noopener"
                        >tamazenko@polygraphist.kiev.ua</a
                      >
                    </v-card-text>
                    <v-card-text>
                      2. тиснення можливе безбарвне, золотим, червоним, срібним
                      та білим кольором
                    </v-card-text>
                    <v-card-text>
                      3. допустима кількість символів в 1 рядку залежить від
                      обраного формату блокнота
                    </v-card-text>
                    <v-card-text>
                      4. вартість тиснення від 100 грн + ціна блокнота
                    </v-card-text>
                    <v-card-text>
                      5. робота виконується лише після 100% оплати замовлення
                    </v-card-text>
                    <v-sheet class="left">
                      <img
                        alt="Vue logo"
                        class="logo mx-auto"
                        src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F241%202110.jpg?alt=media&token=a6c9884a-57ad-4c63-8b92-f323eea861d2"
                        width="500"
                        height="500"
                      />
                    </v-sheet>
                  </v-card-text>

                  <v-card-actions>
                    <v-spacer></v-spacer>

                    <v-btn
                      text="Close Dialog"
                      @click="isActive.value = false"
                    ></v-btn>
                  </v-card-actions>
                </v-card>
              </template>
            </v-dialog>
          </v-row>
        </v-sheet>
      </v-col>

      <v-col>
        <v-sheet class="pa-2 ma-2">
          <v-card class="mx-auto" max-width="344" hover elevation="16">
            <v-card-item>
              <v-card-title>
                Щоденник недатований А5, 128 аркушів, клітинка, обкладинка
                баладек зелений
              </v-card-title>
              <v-card-subtitle> Артикул: 241/1 06Б гумка </v-card-subtitle>
            </v-card-item>

            <v-card-text>
              <img
                alt="Vue logo"
                class="logo"
                src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F06B_5209_1974_0.jpg?alt=media&token=6be7226f-0667-48a8-bb31-347eaf73c358"
                width="300"
                height="300"
              />

              <!-- <v-container align-content-center>
              <v-bottom-sheet>
                <template v-slot:activator="{ props }">
                  <v-btn
                  color="primary" v-bind="props" text="Замовити 241/1 06Б гумка"></v-btn>
                </template>

                <v-card
                  title="Для індивідуального тиснення фольгою на цьому виробі вам необхідно узгодити:"
                  text=""
                  imaill="tamazenko@polygraphist.kiev.ua"
                >
                <v-card-text>
                1. заповнити макет
                 <a href="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0firebase.xlsx?alt=media&token=63c3e144-60e8-4691-b2ae-b48646990171" target="_blank" rel="noopener">Excel</a>
                 та відправити за адресою
                  <a href="" target="_blank" rel="noopener">tamazenko@polygraphist.kiev.ua</a>
                 </v-card-text>
                 <v-card-text>
                2. тиснення можливе безбарвне, а також золотим, червоним, срібним та білим кольором
                 </v-card-text>
                                  <v-card-text>
                3. допустима кількість символів в 1 рядку залежить від обраного формату блокнота
                 </v-card-text>
                                  <v-card-text>
                4. вартість тиснення від 100 грн + ціна блокнота
                 </v-card-text>
                                                   <v-card-text>
                5. робота виконується лише після 100% оплати замовлення
                 </v-card-text>


                  <img alt="Vue logo" class="logo" src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F06B_5209_1974_0.jpg?alt=media&token=6be7226f-0667-48a8-bb31-347eaf73c358" width="300" height="300" />

                </v-card>
              </v-bottom-sheet>
            </v-container> -->

              Діловий щоденник недатований. Формат 145х202 мм. Кількість
              сторінок 352. Блок кремовий офсет 70г/м2, лінія. Колір капталу та
              лясе - золотий. Мова укр., англ. Перфоровані відривні кутики.
              Форзац - кольорові мапи Європи і України. Обкладинка гнучка,
              штучна шкіра, на гумці.Інформаційний блок містить:-Валюти країн
              світу-Позначення країн та територій в Інтернеті-Правила догляду за
              одягом та знаки на етикетці-Розміри одягу та взуття-Одиниці для
              вимірювання фізичних величин-Офіційні правила тлумачення
              торгівельних термінів міжнародної торгової палати Інкотермс
              2020-Автомобільні коди країни-Часові пояси-Відстані між
              європейськими містами та між обласними центрами України-Довідкові
              телефони-Телефонні коди міст України-Міжнародні телефонні
              коди-Міжнародні штрихові коди.
            </v-card-text>
          </v-card>

          <v-row justify="center">
            <v-dialog width="800">
              <template v-slot:activator="{ props }">
                <v-btn color="primary" v-bind="props" text="Open Dialog">
                </v-btn>
              </template>

              <template v-slot:default="{ isActive }">
                <v-card title="Dialog">
                  <v-card-text>
                    <v-card-title>
                      <span class="text-h5"
                        >Для індивідуального тиснення фольгою вам
                        необхідно:</span
                      >
                    </v-card-title>
                    <v-card-text color="red">
                      1. заповнити макет
                      <a
                        href="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0firebase.xlsx?alt=media&token=63c3e144-60e8-4691-b2ae-b48646990171"
                        target="_blank"
                        rel="noopener"
                        >Excel</a
                      >
                      та відправити за адресою
                      <a href="" target="_blank" rel="noopener"
                        >tamazenko@polygraphist.kiev.ua</a
                      >
                    </v-card-text>
                    <v-card-text>
                      2. тиснення можливе безбарвне, золотим, червоним, срібним
                      та білим кольором
                    </v-card-text>
                    <v-card-text>
                      3. допустима кількість символів в 1 рядку залежить від
                      обраного формату блокнота
                    </v-card-text>
                    <v-card-text>
                      4. вартість тиснення від 100 грн + ціна блокнота
                    </v-card-text>
                    <v-card-text>
                      5. робота виконується лише після 100% оплати замовлення
                    </v-card-text>
                    <v-sheet class="left">
                      <img
                        alt="Vue logo"
                        class="logo mx-auto"
                        src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F06B_5209_1974_0.jpg?alt=media&token=6be7226f-0667-48a8-bb31-347eaf73c358"
                        width="500"
                        height="500"
                      />
                    </v-sheet>
                  </v-card-text>

                  <v-card-actions>
                    <v-spacer></v-spacer>

                    <v-btn
                      text="Close Dialog"
                      @click="isActive.value = false"
                    ></v-btn>
                  </v-card-actions>
                </v-card>
              </template>
            </v-dialog>
          </v-row>
        </v-sheet>
      </v-col>

      <v-col>
        <v-sheet class="pa-2 ma-2">
          <v-card class="mx-auto" max-width="344" elevation="16" hover>
            <v-card-item>
              <v-card-title>
                Записна книжка А5, 128 аркушів, клітинка, обкладинка шт. шкіра
                синя на кнопці, закрас зрізу блока
              </v-card-title>
              <v-card-subtitle> Артикул: 234/2 2252 кнопка </v-card-subtitle>
            </v-card-item>

            <v-card-text>
              <img
                alt="Vue logo"
                class="logo"
                src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F234%202252%20%D0%BA%D0%BD%D0%BE%D0%BF%D0%BA%D0%B0.jpg?alt=media&token=a23c4bc1-675f-4996-9857-29d518d5a33a"
                width="300"
                height="300"
              />

              Діловий щоденник недатований. Формат 145х202 мм. Кількість
              сторінок 352. Блок білий офсет 70г/м2. Колір капталу та лясе -
              білий. Мова укр., англ. Форзац - кольорові мапи України, Європи.
              Матеріал обкладинки штучна шкіра. Інформаційний блок
              містить:-Валюти країн світу-Позначення країн та територій в
              Інтернеті-Правила догляду за одягом та знаки на етикетці-Розміри
              одягу та взуття-Одиниці для вимірювання фізичних величин-Офіційні
              правила тлумачення торгівельних термінів міжнародної торгової
              палати Інкотермс 2020-Автомобільні коди країни-Часові
              пояси-Відстані між європейськими містами та між обласними центрами
              України-Довідкові телефони-Телефонні коди міст України-Міжнародні
              телефонні коди-Міжнародні штрихові коди
            </v-card-text>
          </v-card>

          <v-row justify="center">
            <v-dialog width="800">
              <template v-slot:activator="{ props }">
                <v-btn color="primary" v-bind="props" text="Open Dialog">
                </v-btn>
              </template>

              <template v-slot:default="{ isActive }">
                <v-card title="Dialog">
                  <v-card-text>
                    <v-card-title>
                      <span class="text-h5"
                        >Для індивідуального тиснення фольгою вам
                        необхідно:</span
                      >
                    </v-card-title>
                    <v-card-text color="red">
                      1. заповнити макет
                      <a
                        href="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F%D0%9A%D0%BD%D0%B8%D0%B3%D0%B0firebase.xlsx?alt=media&token=63c3e144-60e8-4691-b2ae-b48646990171"
                        target="_blank"
                        rel="noopener"
                        >Excel</a
                      >
                      та відправити за адресою
                      <a href="" target="_blank" rel="noopener"
                        >tamazenko@polygraphist.kiev.ua</a
                      >
                    </v-card-text>
                    <v-card-text>
                      2. тиснення можливе безбарвне, золотим, червоним, срібним
                      та білим кольором
                    </v-card-text>
                    <v-card-text>
                      3. допустима кількість символів в 1 рядку залежить від
                      обраного формату блокнота
                    </v-card-text>
                    <v-card-text>
                      4. вартість тиснення від 100 грн + ціна блокнота
                    </v-card-text>
                    <v-card-text>
                      5. робота виконується лише після 100% оплати замовлення
                    </v-card-text>
                    <v-sheet class="left">
                      <img
                        alt="Vue logo"
                        class="logo mx-auto"
                        src="https://firebasestorage.googleapis.com/v0/b/cborka.appspot.com/o/foto%2F234%202252%20%D0%BA%D0%BD%D0%BE%D0%BF%D0%BA%D0%B0.jpg?alt=media&token=a23c4bc1-675f-4996-9857-29d518d5a33a"
                        width="500"
                        height="500"
                      />
                    </v-sheet>
                  </v-card-text>

                  <v-card-actions>
                    <v-spacer></v-spacer>

                    <v-btn
                      text="Close Dialog"
                      @click="isActive.value = false"
                    ></v-btn>
                  </v-card-actions>
                </v-card>
              </template>
            </v-dialog>
          </v-row>
        </v-sheet>
      </v-col>
    </v-row>
  </v-container2>
</template>

<script>
export default {
  data() {
    return {
      dialog: false,
    };
  },
};
</script>
