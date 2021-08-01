<template>
  <div>
    <Top />
    <Profit />
    <Explanation />
    <Offer />
    <NeedATeam />
    <WhyUs />
    <Instagram />
    <Contact />
    <Footer />
  </div>
</template>

<script>
import Contact from '../components/page/Contact'
import Explanation from '../components/page/Explanation'
import Footer from '../components/page/Footer'
import Instagram from '../components/page/Instagram'
import NeedATeam from '../components/page/NeedATeam'
import Offer from '../components/page/Offer'
import Profit from '../components/page/Profit'
import Top from '../components/page/Top'
import WhyUs from '../components/page/WhyUs'
export default {
  components: {
    Contact,
    Explanation,
    Footer,
    Instagram,
    NeedATeam,
    Offer,
    Profit,
    Top,
    WhyUs,
  },
}
</script>
