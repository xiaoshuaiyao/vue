<template>
  <div class="home">
    <Header/>
    <Top/>
    <Section/>
    <Container/>
    <Logo/>
    <Pundit/>
    <Nav/>
    <Footer/>
  </div>
</template>

<script>
import Footer from '../components/home/footer'
import Nav from '../components/home/nav'
import Pundit from '../components/home/pundit'
import Logo from '../components/home/logo'
import Container from '../components/home/container'
import Section from '../components/home/section'
import Top from '../components/home/top'
import Header from '../components/home/header'
import Common from '../components/common.css'
export default {
  name: 'Home',
  components: {
      Header,
      Common,
      Top,
      Section,
      Container,
      Logo,
      Pundit,
      Nav,
      Footer
  }
}
</script>
