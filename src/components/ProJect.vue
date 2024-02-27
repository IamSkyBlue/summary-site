<template>
  <v-row no-gutters>
    <v-col cols="12" md="6">
      <v-card class="ma-2">
        <v-img cover src="@/assets/guraeat.jpg" height="350"></v-img>

        <v-card-item>
          <v-card-title class="text-h5 font-weight-bold"
            >gura eAt外送平台</v-card-title
          >
          <v-card-subtitle>
            <span class="me-1">校內專案/團體</span>
          </v-card-subtitle>
          <template v-slot:append>
            <v-btn
              href="https://www.youtube.com/playlist?list=PLqfw7IseuE_gb7W9Yx7LkV4tDBW5-4Cal"
              target="_blank"
              density="comfortable"
              color="surface-variant"
              variant="text"
              icon="mdi-youtube"
            ></v-btn>
            <v-btn
              href="https://github.com/IamSkyBlue/GuraEat"
              target="_blank"
              density="comfortable"
              color="surface-variant"
              variant="text"
              icon="mdi-github"
            ></v-btn>
          </template>
        </v-card-item>
        <v-divider class="mx-4 mb-1"></v-divider>
        <v-card-text
          ><div class="me-1 text-h6">負責內容:</div>
          <div>
            建置前端，包含外送員送餐google地圖介面、訂單狀態同步、餐廳上架功能
          </div>
          <div class="me-1 text-h6">使用技術:</div>
          <div>Vue、Vuetify、Swagger、GoogleMap API、Postman、Heroku</div>
        </v-card-text>
      </v-card>
    </v-col>
    <v-spacer />
    <v-col cols="12" md="6">
      <v-card class="ma-2">
        <v-img cover src="@/assets/grafana.jpg" height="350"></v-img>

        <v-card-item>
          <v-card-title class="text-h5 font-weight-bold"
            >工業場域監測/警報系統</v-card-title
          >
          <v-card-subtitle>
            <span class="me-1">實驗室產學計畫/團體</span>
          </v-card-subtitle>
          <template v-slot:append>
            <v-tooltip text="產學不公開" open-on-click location="bottom">
              <template v-slot:activator="{ props }">
                <div v-bind="props">
                  <v-btn
                    icon="mdi-alert-circle"
                    density="comfortable"
                    color="surface-variant"
                    variant="text"
                    disabled
                  ></v-btn>
                </div>
              </template>
            </v-tooltip>
          </template>
        </v-card-item>
        <v-divider class="mx-4 mb-1"></v-divider>
        <v-card-text
          ><div class="me-1 text-h6">負責內容:</div>
          <div>
            建置/維護整體監控架構、建置/維護 modbus gateway、建置/維護
            Containers
          </div>
          <div class="me-1 text-h6">使用技術:</div>
          <div>Docker、Prometheus、Grafana、Python、Arduino</div>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
  <v-row no-gutters>
    <v-col cols="12" md="6">
      <v-card class="ma-2">
        <v-img cover src="@/assets/ornabot.jpg" height="350"></v-img>

        <v-card-item>
          <v-card-title class="text-h5 font-weight-bold">Ornabot</v-card-title>
          <v-card-subtitle>
            <span class="me-1">Discord互動機器人/個人side project</span>
          </v-card-subtitle>
          <template v-slot:append>
            <v-btn
              href="https://github.com/IamSkyBlue/TC_orna_bot"
              target="_blank"
              density="comfortable"
              color="surface-variant"
              variant="text"
              icon="mdi-github"
            ></v-btn>
          </template>
        </v-card-item>
        <v-divider class="mx-4 mb-1"></v-divider>
        <v-card-text
          ><div class="me-1 text-h6">負責內容:</div>
          <div>建置/維護機器人</div>
          <div class="me-1 text-h6">使用技術:</div>
          <div>Python、Google API(visionAPI、sheetAPI)</div>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" md="6">
      <v-card class="ma-2">
        <v-img cover src="@/assets/AI.jpg" height="350"></v-img>

        <v-card-item>
          <v-card-title class="text-h5 font-weight-bold"
            >AI帶你走進動漫世界</v-card-title
          >
          <v-card-subtitle>
            <span class="me-1">大學畢業專題/團體</span>
          </v-card-subtitle>
          <template v-slot:append>
            <v-btn
              href="https://www.youtube.com/watch?v=zipwFd8Gvyc"
              target="_blank"
              density="comfortable"
              color="surface-variant"
              variant="text"
              icon="mdi-youtube"
            ></v-btn>
            <v-btn
              href="https://drive.google.com/file/d/1mBgJjVWt8Ih8JLnT-kdaSmil3ExXIEva/view"
              target="_blank"
              density="comfortable"
              color="surface-variant"
              variant="text"
              icon="mdi-note-text"
            ></v-btn>
          </template>
        </v-card-item>
        <v-divider class="mx-4 mb-1"></v-divider>
        <v-card-text
          ><div class="me-1 text-h6">負責內容:</div>
          <div>Mask-rcnn裁切/拼接臉部、測試各模型效果</div>
          <div class="me-1 text-h6">使用技術:</div>
          <div>Python、Mask-rcnn、GANs</div>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" md="6">
      <v-card class="ma-2">
        <v-img cover src="@/assets/sasp.jpg" height="350"></v-img>

        <v-card-item>
          <v-card-title class="text-h5 font-weight-bold"
            >SASP:SASP Auto Save Photo</v-card-title
          >
          <v-card-subtitle>
            <span class="me-1">Line機器人/個人side project</span>
          </v-card-subtitle>
          <template v-slot:append>
            <v-btn
              href="https://github.com/IamSkyBlue/SASP"
              target="_blank"
              density="comfortable"
              color="surface-variant"
              variant="text"
              icon="mdi-github"
            ></v-btn>
          </template>
        </v-card-item>
        <v-divider class="mx-4 mb-1"></v-divider>
        <v-card-text
          ><div class="me-1 text-h6">負責內容:</div>
          <div>建置/維護機器人</div>
          <div class="me-1 text-h6">使用技術:</div>
          <div>Python、flask、Line API、Google Drive API</div>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" md="6">
      <v-card class="ma-2">
        <v-img cover src="@/assets/darkwood.jpg" height="350"></v-img>

        <v-card-item>
          <v-card-title class="text-h5 font-weight-bold">Darkwood</v-card-title>
          <v-card-subtitle>
            <span class="me-1">校內專案/雙人</span>
          </v-card-subtitle>
          <template v-slot:append>
            <v-btn
              href="https://iamskyblue.github.io/darkwood"
              target="_blank"
              density="comfortable"
              color="surface-variant"
              variant="text"
              icon="mdi-gamepad-square"
            ></v-btn>
            <v-btn
              href="https://docs.google.com/presentation/d/1AvGYQFg_C8gvJ-aD4bQIB3btmloUagNpewnNGAFvVF4/edit?usp=sharing"
              target="_blank"
              density="comfortable"
              color="surface-variant"
              variant="text"
              icon="mdi-file-powerpoint"
            ></v-btn>
          </template>
        </v-card-item>
        <v-divider class="mx-4 mb-1"></v-divider>
        <v-card-text
          ><div class="me-1 text-h6">負責內容:</div>
          <div>建置網頁大部分內容</div>
          <div class="me-1 text-h6">使用技術:</div>
          <div>HTML、JS、jquery</div>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
</script>