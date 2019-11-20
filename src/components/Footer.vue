<template>
  <!-- Footer -->
  <mdb-footer color="blue" class="font-small pt-4 mt-4">
    <mdb-container class="text-left">
      <mdb-row>
        <mdb-col sm="6">
          <h5 class="title">Footer Content</h5>
          <font-awesome-icon :icon="{ prefix: 'fab', iconName: 'facebook' }"/>
          <font-awesome-icon :icon="{ prefix: 'fab', iconName: 'google' }"/>
          <p>Here you can use rows and columns here to organize your footer content.</p>
          <font-awesome-icon icon="faGrinHearts"></font-awesome-icon>
          <font-awesome-icon :icon="{prefix: 'fab',  iconName:'faGrinHearts'}" />
        </mdb-col>
        <mdb-col sm="6">
          <h5 class="title">Links</h5>
          <ul>
            <li class="list-unstyled"><a href="#!">Link 1</a></li>
            <li class="list-unstyled"><a href="#!">Link 2</a></li>
            <li class="list-unstyled"><a href="#!">Link 3</a></li>
            <li class="list-unstyled"><a href="#!">Link 4</a></li>
          </ul>
        </mdb-col>
      </mdb-row>

    </mdb-container>
    <div class="footer-copyright text-center py-3">
      <mdb-container fluid>
        &copy; 2018 Copyright: <a href="https://www.MDBootstrap.com"> MDBootstrap.com </a>
      </mdb-container>
    </div>
  </mdb-footer>
  <!-- Footer -->
</template>

<script>
  export default {
    name: 'Footer'
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  h3 {
    margin: 40px 0 0;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
