<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>№1</template>

    <a href="https://v.org/" target="_blank" rel="noopener">Іменне тиснення за 15 хвилин</a>
    За Вашим бажанням ми виконуємо тиснення імені та прізвища, ініціалів, слоганів, коротких побажань тощо. Умови:
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>№2</template>

    <a href="https://v.org/" target="_blank" rel="noopener"></a>
    тиснення виконується на блокнотах з твердою обкладинкою

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>№3</template>

    <a href="https://v.org/" target="_blank" rel="noopener"></a>
    можливе “сліпе” тиснення, а також золотим, срібним та білим кольором, 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>№4</template>

    <a href="https://v.org/" target="_blank" rel="noopener"></a>
    для оформлення замовлення необхідно заповнити коротку форму <a href="https://onedrive.live.com/edit.aspx?resid=534247FB5DE9C65A!6079&ithint=file%2cxlsx&wdo=2&authkey=!AGJb2DYKPTKXM-4" target="_blank" rel="noopener">Excel</a> та відправити її за адресою 
       tamazenko@polygraphist.kiev.ua

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>№5</template>

    <a href="https://v.org/" target="_blank" rel="noopener"></a>
    вартість тиснення від 100 грн
  </WelcomeItem>
</template>
