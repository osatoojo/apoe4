<template>
  <div>
    <WelcomeSection/>
    <FeatureSection/>
    <AppSection/>
  </div>
</template>

<script>
import WelcomeSection from "@/components/home/WelcomeSection";
import FeatureSection from "@/components/home/FeatureSection";
import AppSection from "@/components/home/AppSection";

export default {
  components: {
    WelcomeSection,
    FeatureSection,
    AppSection
  },
  data() {
    return {};
  },
  mounted() {
    document.title = "Home";
  }
};
</script>
