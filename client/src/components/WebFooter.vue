<template>
  <footer class="page-footer">
    <div class="container">
      <div class="row">
        <div class="col s4">
          <a href="#"><img src="" alt="Project Logo" /></a>
          <h5 class="white-text">Contact</h5>
          <p>+855 123 456 789</p>
          <p>tvna19@kit.edu.kh</p>
          <p></p>
        </div>

        <div class="col s4">
          <h5 class="white-text">Information</h5>
          <ul>
            <li><a class="grey-text text-lighten-3" href="#!">About</a></li>
            <li><a class="grey-text text-lighten-3" href="#!">FAQ</a></li>
            <li>
              <a class="grey-text text-lighten-3" href="#!">Term&Condition</a>
            </li>
            <li>
              <a class="grey-text text-lighten-3" href="#!">Privacy Policy</a>
            </li>
          </ul>
        </div>
        <div class="col s4">
          <div class="row">
            <br />
            <p style="font-size: 16px">Subscribe for more info</p>
            <form class="col s12">
              <div class="row">
                <div class="input-field col s12">
                  <input
                    id="email"
                    type="email"
                    placeholder="Enter your Email"
                  />
                  <input
                    id="submit"
                    type="submit"
                    value="Subscibe"
                    class="btn waves-effect waves-light"
                  />
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-copyright">
      <div class="container">
        <center><p>© 2020 Copyright TvNa.com.kh</p></center>
      </div>
    </div>
  </footer>
</template>
<style>
.page-footer {
  background-color: #00c689;
}
#email {
  border-radius: 10px;
  border: 2px solid;
  padding-left: 10px;
  text-decoration: none;
}
</style>