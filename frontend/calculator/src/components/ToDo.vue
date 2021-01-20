<template>
  <div>
      <b-navbar type="dark" variant="info">
    <b-navbar-brand href="#">NavBar</b-navbar-brand>
      </b-navbar>
    <h1>hello</h1>
    <b-container fluid>
      <b-row>
        <b-col
          >1 of 2

          <b-card>
            <b-tabs content-class="mt-3 ml-10">
              <b-tab title="First"><p>I'm the first tab</p></b-tab>
              <b-tab title="Second" active><p>I'm the second tab</p></b-tab>
              <b-tab title="Disabled"><p>I'm a disabled tab!</p></b-tab>
            </b-tabs>
          </b-card>
        </b-col>
        <b-col>2 of 2</b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>