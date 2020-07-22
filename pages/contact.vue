<template>
  <div class="container">
    <div class="content d-flex flex-column align-items-center justify-content-center">
      <div class="row">
        <div class="col-lg-12">
          <ul class="list-unstyled">
            <li class="pb-3">
              <h1>
                <font-awesome-icon icon="globe" class="mr-3" />
                Auckland, New Zealand
              </h1>
            </li>
            <li class="pb-3">
              <h1>
                <font-awesome-icon icon="envelope" class="mr-3" />
                <a href="mailto:zzkevinlim@gmail.com">zzkevinlim@gmail.com</a>
              </h1>
            </li>
            <li class="pb-3">
              <h1>
                <font-awesome-icon icon="link" class="mr-3" />
                <a href="https://linkedin.com/in/zzkevinlim" target="_blank">linkedin.com/in/zzkevinlim</a>
              </h1>
            </li>
            <li class="pb-3">
              <h1>
                <font-awesome-icon icon="link" class="mr-3" />
                <a href="https://github.com/zzkevinlim" target="_blank">github.com/zzkevinlim</a>
              </h1>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .content {
    height: calc(100vh - 100px);
  }

  svg {
    @media (max-width: 991px) {
      display: none;
    }
  }
</style>
