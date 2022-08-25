<template>
  <div>
    <Head>
      <Title>Ecojobz</Title>
      <Meta name="description" content="Ecolabz site" />
    </Head>
    <!-- Navigation -->
    <nav>
      <div class="nav-item-container">
        <!-- Logo -->

        <NuxtLink class="navbar-brand logo-image" to="/"
          ><img src="@/assets/icons/logo.svg" alt="logo"
        /></NuxtLink>
        <!-- End of Logo -->

        <ul class="nav-item-list">
          <li @click="removeNavbar" class="nav-item">
            <NuxtLink class="nav-link" to="/">Post a job</NuxtLink>
          </li>
          <li @click="removeNavbar" class="nav-item">
            <NuxtLink class="nav-link" to="/">About</NuxtLink>
          </li>
          <li @click="removeNavbar" class="nav-item">
            <NuxtLink class="nav-link" to="/">Login</NuxtLink>
          </li>
          <li @click="removeNavbar" class="nav-item">
            <NuxtLink class="nav-link" to="/"
              ><span>Get Started</span>
              <img src="@/assets/icons/chevron-right.svg" alt=""
            /></NuxtLink>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Menu -->
    <div class="menu-btn">
      <div @click="toggleMenu" class="menu-btn__burger"></div>
    </div>
    <!-- End of Navigation -->

    <!-- Hero Section -->
    <header>
      <h1>
        Hire the best
        <span><img src="@/assets/images/hero-image-01.svg" alt="" /></span>
        freelancer for your design and development
        <span><img src="@/assets/images/hero-image-02.svg" alt="" /></span>
        project
      </h1>
    </header>

    <!-- End of Hero Section -->

    <!-- Carousel Section -->
    <div id="paginated_gallery" class="gallery">
      <div class="gallery_scroller">
        <img src="@/assets/images/slider-placeholder-01.png" alt="..." />
        <img src="@/assets/images/slider-placeholder-02.png" alt="..." />
        <img src="@/assets/images/slider-placeholder-03.png" alt="..." />
        <img src="@/assets/images/slider-placeholder-01.png" alt="..." />
        <img src="@/assets/images/slider-placeholder-01.png" alt="..." />
        <img src="@/assets/images/slider-placeholder-02.png" alt="..." />
        <img src="@/assets/images/slider-placeholder-03.png" alt="..." />
        <img src="@/assets/images/slider-placeholder-01.png" alt="..." />
      </div>
      <span @click="scrollToPrevPage" class="btn prev"></span>
      <span @click="scrollToNextPage" class="btn next"></span>
    </div>

    <!-- End of Carousel Section -->

    <!-- Featured Jobs -->
    <div class="featured-jobs">
      <div class="text-center"><h1>Featured Jobs</h1></div>
      <div class="container-lg">
        <div class="row align-items-center justify-content-between">
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="jobs-card">
              <div class="list-item">
                <div class="item">
                  Design
                  <div class="icon"></div>
                </div>
                <div class="item">
                  Development
                  <div class="icon"></div>
                </div>
                <div class="item">
                  UI/UX
                  <div class="icon"></div>
                </div>
              </div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
                maiores et reiciendis dolores, odio cumque dolor suscipit nulla,
                fuga iure, consequatur ullam esse iste mollitia quis adipisci!
                Nihil incidunt veniam quo ullam quod perferendis? Perspiciatis
                qui mollitia aut eius corporis exercitationem, consequatur
                officiis illo blanditiis facilis aperiam corrupti odit nihil
                quaerat id error consequuntur dolorum? Tempora id eligendi
                commodi. Quam quia aperiam obcaecati, alias voluptate ea
                quisquam molestiae sed cupiditate, architecto tempora
                reprehenderit quasi nemo, ad vel placeat fuga non! Assumenda, ad
                ipsum. Atque, dolore unde. Reiciendis cupiditate dolorum autem
                nisi cumque quaerat laborum alias quis mollitia nesciunt, hic
                dolor!
              </p>
              <div class="location">
                <img src="@/assets/icons/location.svg" alt="Location Icon" />
                <div class="option">Remote <span>|</span></div>
                <div class="option">Worldwide <span>|</span></div>
                <div class="option">USA <span>|</span></div>
              </div>
              <div class="divider"></div>
              <div class="date-bid">
                <div class="date">3 Days ago</div>
                <div class="bid">Bid</div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="jobs-card">
              <div class="list-item">
                <div class="item">
                  Design
                  <div class="icon"></div>
                </div>
                <div class="item">
                  Development
                  <div class="icon"></div>
                </div>
              </div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
                maiores et reiciendis dolores, odio cumque dolor suscipit nulla,
                fuga iure, consequatur ullam esse iste mollitia quis adipisci!
                Nihil incidunt veniam quo ullam quod perferendis? Perspiciatis
                qui mollitia aut eius corporis exercitationem, consequatur
                officiis illo blanditiis facilis aperiam corrupti odit nihil
                quaerat id error consequuntur dolorum? Tempora id eligendi
                commodi. Quam quia aperiam obcaecati, alias voluptate ea
                quisquam molestiae sed cupiditate, architecto tempora
                reprehenderit quasi nemo, ad vel placeat fuga non! Assumenda, ad
                ipsum. Atque, dolore unde. Reiciendis cupiditate dolorum autem
                nisi cumque quaerat laborum alias quis mollitia nesciunt, hic
                dolor!
              </p>
              <div class="location">
                <img src="@/assets/icons/location.svg" alt="Location Icon" />
                <div class="option">Remote <span>|</span></div>
                <div class="option">Worldwide <span>|</span></div>
              </div>
              <div class="divider"></div>
              <div class="date-bid">
                <div class="date">3 Days ago</div>
                <div class="bid">Bid</div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="jobs-card">
              <div class="list-item">
                <div class="item">
                  Design
                  <div class="icon"></div>
                </div>
                <div class="item">
                  Development
                  <div class="icon"></div>
                </div>
              </div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
                maiores et reiciendis dolores, odio cumque dolor suscipit nulla,
                fuga iure, consequatur ullam esse iste mollitia quis adipisci!
                Nihil incidunt veniam quo ullam quod perferendis? Perspiciatis
                qui mollitia aut eius corporis exercitationem, consequatur
                officiis illo blanditiis facilis aperiam corrupti odit nihil
                quaerat id error consequuntur dolorum? Tempora id eligendi
                commodi. Quam quia aperiam obcaecati, alias voluptate ea
                quisquam molestiae sed cupiditate, architecto tempora
                reprehenderit quasi nemo, ad vel placeat fuga non! Assumenda, ad
                ipsum. Atque, dolore unde. Reiciendis cupiditate dolorum autem
                nisi cumque quaerat laborum alias quis mollitia nesciunt, hic
                dolor!
              </p>
              <div class="location">
                <img src="@/assets/icons/location.svg" alt="Location Icon" />
                <div class="option">Remote <span>|</span></div>
                <div class="option">Worldwide <span>|</span></div>
                <div class="option">USA <span>|</span></div>
              </div>
              <div class="divider"></div>
              <div class="date-bid">
                <div class="date">3 Days ago</div>
                <div class="bid">Bid</div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="jobs-card">
              <div class="list-item">
                <div class="item">
                  Design
                  <div class="icon"></div>
                </div>
                <div class="item">
                  Development
                  <div class="icon"></div>
                </div>
              </div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
                maiores et reiciendis dolores, odio cumque dolor suscipit nulla,
                fuga iure, consequatur ullam esse iste mollitia quis adipisci!
                Nihil incidunt veniam quo ullam quod perferendis? Perspiciatis
                qui mollitia aut eius corporis exercitationem, consequatur
                officiis illo blanditiis facilis aperiam corrupti odit nihil
                quaerat id error consequuntur dolorum? Tempora id eligendi
                commodi. Quam quia aperiam obcaecati, alias voluptate ea
                quisquam molestiae sed cupiditate, architecto tempora
                reprehenderit quasi nemo, ad vel placeat fuga non! Assumenda, ad
                ipsum. Atque, dolore unde. Reiciendis cupiditate dolorum autem
                nisi cumque quaerat laborum alias quis mollitia nesciunt, hic
                dolor!
              </p>
              <div class="location">
                <img src="@/assets/icons/location.svg" alt="Location Icon" />
                <div class="option">Remote <span>|</span></div>
                <div class="option">Worldwide <span>|</span></div>
                <div class="option">USA <span>|</span></div>
              </div>
              <div class="divider"></div>
              <div class="date-bid">
                <div class="date">3 Days ago</div>
                <div class="bid">Bid</div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="jobs-card">
              <div class="list-item">
                <div class="item">
                  Design
                  <div class="icon"></div>
                </div>
                <div class="item">
                  Development
                  <div class="icon"></div>
                </div>
              </div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
                maiores et reiciendis dolores, odio cumque dolor suscipit nulla,
                fuga iure, consequatur ullam esse iste mollitia quis adipisci!
                Nihil incidunt veniam quo ullam quod perferendis? Perspiciatis
                qui mollitia aut eius corporis exercitationem, consequatur
                officiis illo blanditiis facilis aperiam corrupti odit nihil
                quaerat id error consequuntur dolorum? Tempora id eligendi
                commodi. Quam quia aperiam obcaecati, alias voluptate ea
                quisquam molestiae sed cupiditate, architecto tempora
                reprehenderit quasi nemo, ad vel placeat fuga non! Assumenda, ad
                ipsum. Atque, dolore unde. Reiciendis cupiditate dolorum autem
                nisi cumque quaerat laborum alias quis mollitia nesciunt, hic
                dolor!
              </p>
              <div class="location">
                <img src="@/assets/icons/location.svg" alt="Location Icon" />
                <div class="option">Remote <span>|</span></div>
                <div class="option">Worldwide <span>|</span></div>
                <div class="option">USA <span>|</span></div>
              </div>
              <div class="divider"></div>
              <div class="date-bid">
                <div class="date">3 Days ago</div>
                <div class="bid">Bid</div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="jobs-card">
              <div class="list-item">
                <div class="item">
                  Design
                  <div class="icon"></div>
                </div>
                <div class="item">
                  Development
                  <div class="icon"></div>
                </div>
              </div>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
                maiores et reiciendis dolores, odio cumque dolor suscipit nulla,
                fuga iure, consequatur ullam esse iste mollitia quis adipisci!
                Nihil incidunt veniam quo ullam quod perferendis? Perspiciatis
                qui mollitia aut eius corporis exercitationem, consequatur
                officiis illo blanditiis facilis aperiam corrupti odit nihil
                quaerat id error consequuntur dolorum? Tempora id eligendi
                commodi. Quam quia aperiam obcaecati, alias voluptate ea
                quisquam molestiae sed cupiditate, architecto tempora
                reprehenderit quasi nemo, ad vel placeat fuga non! Assumenda, ad
                ipsum. Atque, dolore unde. Reiciendis cupiditate dolorum autem
                nisi cumque quaerat laborum alias quis mollitia nesciunt, hic
                dolor!
              </p>
              <div class="location">
                <img src="@/assets/icons/location.svg" alt="Location Icon" />
                <div class="option">Remote <span>|</span></div>
                <div class="option">Worldwide <span>|</span></div>
                <div class="option">USA <span>|</span></div>
              </div>
              <div class="divider"></div>
              <div class="date-bid">
                <div class="date">3 Days ago</div>
                <div class="bid">Bid</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End of Featured Jobs -->

    <!-- How-We-Work -->
    <div class="how-we-work">
      <div class="text-center"><h1>How We Work</h1></div>
      <div class="container-lg">
        <div class="row align-items-center justify-content-between">
          <div class="col-12 col-sm-6 col-lg-6 work-flow">
            <div class="row align-items-center justify-content-between">
              <div class="col-6">
                <img
                  src="@/assets/images/how-we-work-01.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="col-6">
                <div class="instruction">
                  <h4>01</h4>
                  <h5>Create a free account</h5>
                  <p>
                    Get started by loggin into your account or creating a free
                    account and following the easy steps.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-6 work-flow">
            <div class="row align-items-center justify-content-between">
              <div class="col-6">
                <img
                  src="@/assets/images/how-we-work-02.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="col-6">
                <div class="instruction">
                  <h4>02</h4>
                  <h5>Set up a profile</h5>
                  <p>
                    By using a video meeting platform, our team can connect with
                    you as a client and discuss your needs.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-6 work-flow">
            <div class="row align-items-center justify-content-between">
              <div class="col-6">
                <img
                  src="@/assets/images/how-we-work-03.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="col-6">
                <div class="instruction">
                  <h4>03</h4>
                  <h5>Bid for a project</h5>
                  <p>
                    By using a video meeting platform, our team can connect with
                    you as a client and discuss your needs.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-6 work-flow">
            <div class="row align-items-center justify-content-between">
              <div class="col-6">
                <img
                  src="@/assets/images/how-we-work-04.png"
                  class="img-fluid"
                  alt=""
                />
              </div>
              <div class="col-6">
                <div class="instruction">
                  <h4>03</h4>
                  <h5>Bid for a project</h5>
                  <p>
                    By using a video meeting platform, our team can connect with
                    you as a client and discuss your needs.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End of How-We-Work -->

    <!-- Get Reviewed -->

    <div class="get-reviewed">
      <div class="text-center"><h1>Get Reviewed</h1></div>

      <div class="container-lg">
        <div class="review-blur">
          <div
            class="
              row
              align-items-center
              justify-content-sm-around justify-content-between
            "
          >
            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-01.svg" alt="" />
                  <div>
                    <div class="name">Darin Nguyen</div>
                    <div class="username">@staking</div>
                  </div>
                </div>
                <p>Faucibus eu condimentum maecenas sollicitudin vitae.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>

            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-01.svg" alt="" />
                  <div>
                    <div class="name">Darin Nguyen</div>
                    <div class="username">@staking</div>
                  </div>
                </div>
                <p>Faucibus eu condimentum maecenas sollicitudin vitae.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>

            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-02.svg" alt="" />
                  <div>
                    <div class="name">Nur Wainwright</div>
                    <div class="username">@flawless</div>
                  </div>
                </div>
                <p>
                  Volutpat nec, dictumst adipiscing mauris molestie a. Proin sit
                  libero tristique suspendisse.
                </p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>

            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-02.svg" alt="" />
                  <div>
                    <div class="name">Nur Wainwright</div>
                    <div class="username">@flawless</div>
                  </div>
                </div>
                <p>
                  There’s no other program that walks you through exactly what
                  you need to know to start an online store fast, written by
                  someone who has built several 7-figure ecommerce businesses
                  from scratch.
                </p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-03.svg" alt="" />
                  <div>
                    <div class="name">Farah Morin</div>
                    <div class="username">@lice</div>
                  </div>
                </div>
                <p>
                  Montes, ornare purus vestibulum, eget nec sem velit. Pharetra
                  dolor auctor facilisis nunc condimentum orci massa.
                </p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>

            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-03.svg" alt="" />
                  <div>
                    <div class="name">Farah Morin</div>
                    <div class="username">@lice</div>
                  </div>
                </div>
                <p>
                  There’s no other program that walks you through exactly what
                  you need to know to start an online store fast, written by
                  someone who has built several 7-figure ecommerce businesses
                  from scratch.
                </p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>

            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-05.svg" alt="" />
                  <div>
                    <div class="name">Glen Barton</div>
                    <div class="username">@forth</div>
                  </div>
                </div>
                <p>
                  Montes, ornare purus vestibulum, eget nec sem velit. Pharetra
                  dolor auctor facilisis nunc condimentum orci massa.
                </p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-05.svg" alt="" />
                  <div>
                    <div class="name">Glen Barton</div>
                    <div class="username">@forth</div>
                  </div>
                </div>
                <p>Nisl, eget imperdiet pharetra consectetur.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-01.svg" alt="" />
                  <div>
                    <div class="name">Darin Nguyen</div>
                    <div class="username">@staking</div>
                  </div>
                </div>
                <p>Faucibus eu condimentum maecenas sollicitudin vitae.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-01.svg" alt="" />
                  <div>
                    <div class="name">Darin Nguyen</div>
                    <div class="username">@staking</div>
                  </div>
                </div>
                <p>Faucibus eu condimentum maecenas sollicitudin vitae.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-01.svg" alt="" />
                  <div>
                    <div class="name">Darin Nguyen</div>
                    <div class="username">@staking</div>
                  </div>
                </div>
                <p>Faucibus eu condimentum maecenas sollicitudin vitae.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-03.svg" alt="" />
                  <div>
                    <div class="name">Darin Nguyen</div>
                    <div class="username">@staking</div>
                  </div>
                </div>
                <p>Faucibus eu condimentum maecenas sollicitudin vitae.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-02.svg" alt="" />
                  <div>
                    <div class="name">Darin Nguyen</div>
                    <div class="username">@staking</div>
                  </div>
                </div>
                <p>Faucibus eu condimentum maecenas sollicitudin vitae.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
            <div class="col-12 col-sm-6 col-lg-5">
              <div class="review-card">
                <div class="img-name">
                  <img src="@/assets/images/placeholder-01.svg" alt="" />
                  <div>
                    <div class="name">Darin Nguyen</div>
                    <div class="username">@staking</div>
                  </div>
                </div>
                <p>Faucibus eu condimentum maecenas sollicitudin vitae.</p>
                <div class="link-date">
                  <NuxtLink class="link" to="/" target="_blank">
                    Show original
                  </NuxtLink>
                  <div class="date">22.03.2021</div>
                </div>
              </div>
            </div>
          </div>

          <div class="blur"></div>
        </div>
      </div>
      <div class="text-center large-button">
        <button>Large button</button>
      </div>
    </div>

    <!-- End of Get Reviewed -->

    <!-- Subscribe Section -->
    <div class="subscribe">
      <div class="subscribe-border">
        <div class="text-center">
          <h2>Subscribe to get latest updates and news</h2>
        </div>
        <div class="form-box">
          <input type="text" placeholder="Type your e-mail" />
          <div class="text-end"><button>Subscribe</button></div>
        </div>
      </div>
    </div>
    <!-- End of Subscribe Section -->

    <!-- Footer -->
    <div class="footer-bg">
      <div class="container-lg">
        <footer>
          <div class="row align-items-start justify-content-between">
            <div class="col-12 col-sm-6 col-lg-4">
              <div class="footer-logo">
                <img src="@/assets/icons/footer-logo.svg" alt="" />
              </div>
              <div class="description">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
                ornare cursus sed nunc eget dictum Sed ornare cursus sed nunc
                eget dictumd nunc eget dictum Sed ornare cursus sed nunc eget
                dictum Sed ornare cursus sed nunc eget dictumd nunc eget dictum
                Sed ornare cursus sed nunc eget dictum
              </div>
            </div>
            <div class="col-6 col-sm-4 col-lg-2">
              <h4>Company</h4>
              <NuxtLink class="footer-link" to="" target="_blank">
                Home
              </NuxtLink>
              <NuxtLink class="footer-link" to="/" target="_blank">
                About
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                FAQS
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                Contact
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                Privacy Policy
              </NuxtLink>
            </div>
            <div class="col-6 col-sm-4 col-lg-2">
              <h4>Product</h4>
              <NuxtLink class="footer-link" to="" target="_blank">
                Pricing
              </NuxtLink>
              <NuxtLink class="footer-link" to="/" target="_blank">
                Customers
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                Screen Recorder
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                Loom for Enterprise
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                Webcam
              </NuxtLink>
            </div>
            <div class="col-6 col-sm-4 col-lg-2">
              <h4>Resources</h4>
              <NuxtLink class="footer-link" to="" target="_blank">
                Blog
              </NuxtLink>
              <NuxtLink class="footer-link" to="/" target="_blank">
                Attendance
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                Certificates
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                Certificates Verify
              </NuxtLink>
            </div>
            <div class="col-6 col-sm-4 col-lg-2">
              <h4>Help & Information</h4>
              <NuxtLink class="footer-link" to="" target="_blank">
                Help
              </NuxtLink>
              <NuxtLink class="footer-link" to="/" target="_blank">
                Track Order
              </NuxtLink>
              <NuxtLink class="footer-link" to="" target="_blank">
                Delivery and Returns
              </NuxtLink>
            </div>
          </div>
          <div class="social-media">
            <NuxtLink
              class="me-4"
              to="https://instagram.com/ecolabz"
              target="_blank"
              rel="noopener"
            >
              <img src="@/assets/icons/twitter.svg" alt="Twitter" />
            </NuxtLink>
            <NuxtLink
              class="me-4"
              to="https://instagram.com/ecolabz"
              target="_blank"
              rel="noopener"
            >
              <img src="@/assets/icons/meta.svg" alt="Meta" />
            </NuxtLink>

            <NuxtLink
              class="me-4"
              to="https://instagram.com/ecolabz"
              target="_blank"
              rel="noopener"
            >
              <img src="@/assets/icons/linkedin.svg" alt="LinkedIn" />
            </NuxtLink>

            <NuxtLink
              class="me-4"
              to="https://instagram.com/ecolabz"
              target="_blank"
              rel="noopener"
            >
              <img src="@/assets/icons/instagram.svg" alt="Instagram" />
            </NuxtLink>
          </div>
        </footer>
      </div>
    </div>
  </div>
</template>

<script setup>
let menuOpen = false;
const toggleMenu = () => {
  const menuBtn = document.querySelector(".menu-btn");
  const nav = document.querySelector("nav");
  const navItem = document.querySelector(".nav-item-list");

  menuBtn.classList.toggle("active");
  nav.classList.toggle("active");
  navItem.classList.toggle("active");
};

const removeNavbar = () => {
  const menuBtn = document.querySelector(".menu-btn");
  const nav = document.querySelector("nav");
  const navItem = document.querySelector(".nav-item-list");

  menuBtn.classList.toggle("active");
  nav.classList.toggle("active");
  navItem.classList.toggle("active");
};

const scrollToNextPage = () => {
  const gallery = document.querySelector("#paginated_gallery");
  const gallery_scroller = gallery.querySelector(".gallery_scroller");
  const gallery_item_size = gallery_scroller.querySelector("img").clientWidth;
  gallery_scroller.scrollBy(gallery_item_size, 0);
}

const scrollToPrevPage = () => {
   const gallery = document.querySelector("#paginated_gallery");
  const gallery_scroller = gallery.querySelector(".gallery_scroller");
  const gallery_item_size = gallery_scroller.querySelector("img").clientWidth;
  gallery_scroller.scrollBy(-gallery_item_size, 0);
}


</script>

<style>
</style>