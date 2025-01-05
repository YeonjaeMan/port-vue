<!-- script setup : Vue 3에서 도입된 기능, setup() 함수를 사용해 컴포넌트 옵션 정의, 이를 통해 템플릿에서 자동으로 해결되고 제공되는 종속성 가져올 수 있음 -->
<script setup>
// @ 기호는 주로 모듈 번들러에서 사용되는 특별한 경로 별칭(alias)
// 웹 애플리케이션을 번들링하기 위해 사용되는 도구, 여러 개의 JS 파일 및 리소스를 하나의 번들 파일로 결합하여 페이지 로딩 속도를 최적화하는 데 도움을 줌
import HeaderSection from "@/components/HeaderSection.vue";
import FooterSection from "@/components/FooterSection.vue";
import IntroSection from "@/components/IntroSection.vue";
import SkillSection from "@/components/SkillSection.vue";
import SiteSection from "@/components/SiteSection.vue";
import PortSection from "@/components/PortSection.vue";
import ContactSection from "@/components/ContactSection.vue";
import SkipSection from "@/components/SkipSection.vue";
</script>

<template>
    <SkipSection />
    <HeaderSection />
    <main id="main" role="main">
        <IntroSection />
        <SkillSection />
        <SiteSection />
        <PortSection />
        <ContactSection />
    </main>
    <FooterSection />
</template>