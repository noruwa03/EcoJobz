<template>
  <div>
    <Head>
      <Title>Ecojobz</Title>
      <Meta name="description" content="Ecojobz site" />
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
            <NuxtLink class="nav-link" to="/login">Login</NuxtLink>
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
      <div class="hero-row">
        <div class="intro">
          <h1>Hire freelancers to make things happen.</h1>
          <p>
            Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam consequat sunt nostrud amet.
          </p>
          <div class="row-btn">
            <button>Find Job</button>
            <button>Find Freelancer</button>
          </div>
        </div>
        <div class="eclipse">
          <div class="hero-animation">
            <img
              src="@/assets/icons/web-dev.svg"
              class="place-holder-01"
              alt=""
            />
            <img
              src="@/assets/icons/ui-ux.svg"
              class="place-holder-02"
              alt=""
            />
            <img
              src="@/assets/icons/logo-branding.svg"
              class="place-holder-03"
              alt=""
            />
            <img
              src="@/assets/icons/ai-data-model.svg"
              class="place-holder-04"
              alt=""
            />
            <img
              src="@/assets/icons/content-writing.svg"
              class="place-holder-05"
              alt=""
            />
          </div>
        </div>
      </div>
    </header>

    <!-- End of Hero Section -->

    <!-- Popular Category -->
    <div class="popular-category">
      <div class="text-center">
        <h1>Most Popular Categories</h1>
      </div>

      <div class="container-lg">
        <div class="row align-items-center justify-content-between">
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="popular-card">
              <div class="text-center">
                <img src="@/assets/icons/web-dev.svg" alt="" />
                <h3>Website Development</h3>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="popular-card">
              <div class="text-center">
                <img src="@/assets/icons/ui-ux.svg" alt="" />
                <h3>UI/UX Design</h3>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="popular-card">
              <div class="text-center">
                <img src="@/assets/icons/data-analysis.svg" alt="" />
                <h3>Data Analysis</h3>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="popular-card">
              <div class="text-center">
                <img src="@/assets/icons/content-writing.svg" alt="" />
                <h3>Content Writing</h3>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="popular-card">
              <div class="text-center">
                <img src="@/assets/icons/logo-branding.svg" alt="" />
                <h3>Logo Branding</h3>
              </div>
            </div>
          </div>
          <div class="col-12 col-sm-6 col-lg-4">
            <div class="popular-card">
              <div class="text-center">
                <img src="@/assets/icons/ai-data-model.svg" alt="" />
                <h3>AI/Data modeling</h3>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- End of Popular Category -->

    <!-- Background-Image -->
    <div class="bg-container">
      <div class="bg">
        <h1>Get the right people to grow with on Ecojobz easily</h1>

        <div class="job-search">
          <div class="job-card">
            <h3>Job search</h3>
            <p>
              Ask for personalized tips on resumes, interviews and best
              practices in the tech space
            </p>
            <button>Get Started</button>
          </div>
          <div class="job-card">
            <h3>Job search</h3>
            <p>
              Ask for personalized tips on resumes, interviews and best
              practices in the tech space
            </p>
            <button>Get Started</button>
          </div>
          <div class="job-card">
            <h3>Job search</h3>
            <p>
              Ask for personalized tips on resumes, interviews and best
              practices in the tech space
            </p>
            <button>Get Started</button>
          </div>
        </div>
      </div>
    </div>

    <!-- End of Background-Image -->

    <!-- Side by Side Image -->
    <div class="image-container">
      <div class="image-container-one">
        <div class="text-content">
          <h3>Vetted and Verified</h3>
          <p>
            Schedule a session instantly with a mentor and work with them -
            whether it's for one-off tactical advice or multiple sessions
            towards a long-term goal.
          </p>
        </div>
      </div>
      <div class="image-container-two">
        <div class="text-content">
          <h3>Vetted and Verified</h3>
          <p>
            Schedule a session instantly with a mentor and work with them -
            whether it's for one-off tactical advice or multiple sessions
            towards a long-term goal.
          </p>
        </div>
      </div>
    </div>

    <!-- End of Side by Side Image -->

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

    <!-- Featured Jobs -->
    <!-- <div class="featured-jobs">
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
    </div> -->
    <!-- End of Featured Jobs -->

    <!-- Get Reviewed -->

    <div class="get-started">
      <div class="container-lg">
        <div class="row align-items-center justify-content-between">
          <div class="col-12 col-sm-6 col-lg-5">
            <img
              src="@/assets/icons/connect-talent.svg"
              class="img-fluid"
              alt=""
            />
          </div>
          <div class="col-12 col-sm-6 col-lg-5">
            <h1>We help you connect with the right talent</h1>
            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia consequat duis enim velit mollit.
              Exercitation veniam consequat sunt nostrud amet.
            </p>
            <button>
              Get Started
              <img src="@/assets/icons/chevron-right-white.svg" alt="" />
            </button>
          </div>
        </div>
      </div>
    </div>

    <!-- End of Get Started -->

    <div class="connect-talent">
      <div class="connect-row">
        <div class="right-talent">
          <h1>We help you connect with the right talent</h1>
          <p>
            Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
            sint. Velit officia consequat duis enim velit mollit. Exercitation
            veniam consequat sunt nostrud amet.
          </p>
          <button>
            Get Started
            <img src="@/assets/icons/chevron-right-white.svg" alt="" />
          </button>
        </div>
        <div class="cards">
          <div class="talent-card">
            <div class="row-item">
              <img src="@/assets/icons/product-designer.svg" alt="" />
              <h4>Product designer</h4>
            </div>
            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint.
            </p>
          </div>
          <div class="talent-card">
            <div class="row-item">
              <img src="@/assets/icons/frontend-developer.svg" alt="" />
              <h4>Frontend Developer</h4>
            </div>
            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint.
            </p>
          </div>
          <div class="talent-card">
            <div class="row-item">
              <img src="@/assets/icons/visual-designer.svg" alt="" />
              <h4>Visual designer</h4>
            </div>
            <p>
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint.
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- Subscribe Section -->
    <!-- <div class="subscribe">
      <div class="subscribe-border">
        <div class="text-center">
          <h2>Subscribe to get latest updates and news</h2>
        </div>
        <div class="form-box">
          <input type="text" placeholder="Type your e-mail" />
          <div class="btn-end">
            <button>
              Get Started
              <img src="@/assets/icons/chevron-right-white.svg" alt="" />
            </button>
          </div>
        </div>
      </div>
    </div> -->
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
             
            </div>
            <div class="col-6 col-sm-4 col-lg-2">
              <h4>Product</h4>
              <NuxtLink class="footer-link" to="" target="_blank">
                Pricing
              </NuxtLink>
              <NuxtLink class="footer-link" to="/" target="_blank">
                Customers
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
              
            </div>
            <div class="col-6 col-sm-4 col-lg-2">
              <h4>Help & Information</h4>
              <NuxtLink class="footer-link" to="" target="_blank">
                Help
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
</script>

<style>
</style>