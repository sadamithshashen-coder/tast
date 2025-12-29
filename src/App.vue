<template>
  <q-layout view="hHh lpR fFf" class="bg-black text-white">

    <q-header bordered class="bg-black text-white q-py-sm" style="border-bottom: 1px solid rgba(255,255,255,0.1)">
      <q-toolbar>
        <q-toolbar-title class="text-weight-bold text-h5 q-ml-md">
          <q-icon name="dataset" color="primary" size="md" class="q-mr-sm" />
          <span class="text-white">NEXUS</span><span class="text-primary">MGT</span>
        </q-toolbar-title>

        <q-space />

        <div class="q-gutter-x-lg desktop-only row items-center">
          <q-btn flat no-caps label="Home" class="text-white hover-underline" />
          <q-btn flat no-caps label="Features" class="text-grey-4 hover-underline" />
          <q-btn flat no-caps label="Solutions" class="text-grey-4 hover-underline" />
          <q-btn flat no-caps label="Pricing" class="text-grey-4 hover-underline" />
        </div>

        <q-space />

        <div class="row items-center q-gutter-x-sm">
           <q-btn flat no-caps label="Log In" class="text-white desktop-only" />
           <q-btn unelevated color="primary" label="Get Started" no-caps class="q-px-lg rounded-borders" />
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <!-- Hero Section -->
      <section class="hero-section flex flex-center column relative-position overflow-hidden">
        <!-- Background Elements -->
        <div class="absolute-top-right bg-primary blur-effect" style="width: 400px; height: 400px; border-radius: 50%; opacity: 0.15; top: -100px; right: -100px;"></div>
        <div class="absolute-bottom-left bg-primary blur-effect" style="width: 300px; height: 300px; border-radius: 50%; opacity: 0.1; bottom: -50px; left: -50px;"></div>

        <div class="text-center q-pa-md z-top" style="max-width: 900px">
          <div class="q-mb-lg fade-in-up">
             <q-chip color="grey-10" text-color="primary" icon="bolt">
                Next Gen Management System
             </q-chip>
          </div>
          
          <h1 class="text-h1 text-weight-bolder q-mb-md fade-in-up q-mt-none" style="line-height: 1.1; letter-spacing: -2px;">
            Master Your <br/>
            <span class="text-transparent bg-clip-text bg-gradient-primary">Workflow Logic</span>
          </h1>
          
          <p class="text-h6 text-grey-4 q-mb-xl fade-in-up" style="max-width: 600px; margin-left: auto; margin-right: auto; animation-delay: 0.2s;">
            The comprehensive platform engineered to synchronize your team, customers, and operations in one intelligent ecosystem.
          </p>
          
          <div class="q-gutter-md fade-in-up" style="animation-delay: 0.4s;">
            <q-btn color="primary" size="lg" label="Start Free Trial" no-caps icon-right="arrow_forward" class="q-px-xl shadow-10" />
            <q-btn outline color="white" size="lg" label="View Demo" no-caps class="q-px-xl" />
          </div>
        </div>
        
        <!-- Dashboard Preview -->
        <div class="q-mt-xl relative-position full-width flex flex-center fade-in-up" style="animation-delay: 0.6s; perspective: 1000px;">
            <div class="dashboard-preview q-mx-auto" style="transform: rotateX(20deg) scale(0.9);">
                <div class="glass-card q-pa-none rounded-borders overflow-hidden bg-grey-10" style="border: 1px solid rgba(255,255,255,0.1); width: 1000px; max-width: 90vw; height: 500px;">
                    <!-- Fake UI Header -->
                    <div class="row items-center q-pa-sm bg-grey-9 border-bottom">
                       <div class="row q-gutter-x-sm q-px-sm">
                          <div class="circle bg-red-5" style="width: 10px; height: 10px; border-radius: 50%;"></div>
                          <div class="circle bg-yellow-5" style="width: 10px; height: 10px; border-radius: 50%;"></div>
                          <div class="circle bg-green-5" style="width: 10px; height: 10px; border-radius: 50%;"></div>
                       </div>
                       <div class="text-caption text-grey-6 q-ml-md">Nexus Dashboard</div>
                    </div>
                    <!-- Fake UI Content -->
                     <div class="row full-height">
                        <div class="col-2 bg-grey-10 border-right q-pa-md hidden-xs">
                           <div class="q-gutter-y-md">
                              <div class="bg-grey-8 rounded-borders" style="height: 10px; width: 60%;"></div>
                              <div class="bg-grey-9 rounded-borders" style="height: 10px; width: 80%;"></div>
                              <div class="bg-grey-9 rounded-borders" style="height: 10px; width: 70%;"></div>
                           </div>
                        </div>
                        <div class="col bg-black q-pa-lg relative-position">
                             <div class="absolute-center text-center">
                                 <q-spinner-dots size="50px" color="primary" />
                                 <div class="text-grey-6 q-mt-sm">Loading System Data...</div>
                             </div>
                        </div>
                     </div>
                </div>
            </div>
        </div>
      </section>

      <!-- Stats Section -->
      <section class="bg-grey-10 q-py-lg border-y-dim">
          <div class="container row justify-center text-center q-gutter-x-xl q-gutter-y-md">
             <div>
                <div class="text-h3 text-weight-bold text-white">10k+</div>
                <div class="text-uppercase text-caption text-grey-5 letter-spacing-2">Trusted Users</div>
             </div>
             <div>
                 <div class="text-h3 text-weight-bold text-white">99.9%</div>
                 <div class="text-uppercase text-caption text-grey-5 letter-spacing-2">Uptime</div>
             </div>
             <div>
                 <div class="text-h3 text-weight-bold text-white">24/7</div>
                 <div class="text-uppercase text-caption text-grey-5 letter-spacing-2">Support</div>
             </div>
          </div>
      </section>

      <!-- Features Grid -->
      <section class="q-py-xl bg-black relative-position">
        <div class="container q-pa-xl" style="max-width: 1200px; margin: 0 auto;">
            <div class="row items-end q-mb-xl">
                <div class="col-12 col-md-8">
                    <div class="text-primary text-subtitle1 text-weight-bold q-mb-sm">OUR FEATURES</div>
                    <h2 class="text-h3 text-weight-bold text-white q-mt-none">Everything you need to <br/>scale your business.</h2>
                </div>
                <div class="col-12 col-md-4 text-right desktop-only">
                    <q-btn outline color="white" label="Explore All Features" no-caps />
                </div>
            </div>

            <div class="row q-col-gutter-lg">
                <div class="col-12 col-md-4" v-for="(feature, index) in features" :key="index">
                    <q-card class="bg-grey-10 feature-card full-height no-border" square>
                        <q-card-section class="q-pa-lg">
                            <div class="bg-grey-9 inline-block q-pa-md rounded-borders q-mb-lg text-primary">
                                <q-icon :name="feature.icon" size="28px" />
                            </div>
                            <div class="text-h5 text-weight-bold text-white q-mb-md">{{ feature.title }}</div>
                            <div class="text-grey-5 text-body1" style="line-height: 1.6;">
                                {{ feature.desc }}
                            </div>
                        </q-card-section>
                        <q-card-actions class="q-px-lg q-pb-lg">
                           <q-btn flat dense color="primary" label="Learn more" icon-right="arrow_forward" no-caps />
                        </q-card-actions>
                    </q-card>
                </div>
            </div>
        </div>
      </section>

      <!-- Customer Testimonial / Trust -->
      <section class="q-py-xl bg-grey-10 text-center">
         <div class="q-pa-md container" style="max-width: 900px; margin: 0 auto;">
             <q-icon name="format_quote" size="lg" color="primary" class="q-mb-md" />
             <h3 class="text-h4 text-weight-medium text-white italic q-mb-xl">
                 "This system completely revolutionized how we handle our customers and projects. The interface is stunning and the features are exactly what we needed."
             </h3>
             <div class="text-h6 text-white text-weight-bold">Alex Morgan</div>
             <div class="text-primary">CEO of TechFin Global</div>
         </div>
      </section>

       <!-- CTA Section -->
      <section class="q-py-xl text-center bg-black relative-position overflow-hidden">
         <div class="absolute-full bg-gradient-radial blur-effect" style="opacity: 0.2"></div>
         <div class="q-pa-xl relative-position z-top">
            <h2 class="text-h2 text-weight-bold q-mb-md text-white">Start Your Journey Today</h2>
            <p class="text-h6 text-grey-5 q-mb-xl">Join thousands of companies managing their business with Nexus.</p>
             <div class="q-gutter-md">
                <q-btn color="primary" size="xl" label="Get Started Now" no-caps class="q-px-xl" />
             </div>
         </div>
      </section>

    </q-page-container>

    <q-footer class="bg-black text-grey-6 q-py-xl" style="border-top: 1px solid rgba(255,255,255,0.1)">
        <div class="container row q-col-gutter-xl" style="max-width: 1200px; margin: 0 auto;">
            <div class="col-12 col-md-4">
                 <div class="text-h5 text-white text-weight-bold q-mb-md">
                   <span class="text-primary">NEXUS</span>MGT
                 </div>
                 <p>Premium management solutions for the modern enterprise.</p>
            </div>
            <div class="col-6 col-md-2">
                <div class="text-white text-weight-bold q-mb-md">Product</div>
                <div class="q-gutter-y-sm flex column">
                    <a href="#" class="text-grey-6 text-decoration-none hover-text-white">Features</a>
                    <a href="#" class="text-grey-6 text-decoration-none hover-text-white">Pricing</a>
                    <a href="#" class="text-grey-6 text-decoration-none hover-text-white">API</a>
                </div>
            </div>
            <div class="col-6 col-md-2">
                 <div class="text-white text-weight-bold q-mb-md">Company</div>
                 <div class="q-gutter-y-sm flex column">
                    <a href="#" class="text-grey-6 text-decoration-none hover-text-white">About Us</a>
                    <a href="#" class="text-grey-6 text-decoration-none hover-text-white">Careers</a>
                    <a href="mailto:sadamithshashen@gmail.com" class="text-grey-6 text-decoration-none hover-text-white">Contact</a>
                    <div class="text-grey-8 text-caption q-mt-sm">sadamithshashen@gmail.com</div>
                </div>
            </div>
            <div class="col-12 col-md-4">
                <div class="text-white text-weight-bold q-mb-md">Subscribe</div>
                <q-input dark dense outlined placeholder="Enter your email" color="primary">
                    <template v-slot:append>
                        <q-btn flat round color="primary" icon="send" />
                    </template>
                </q-input>
            </div>
        </div>
        <div class="text-center q-mt-xl text-caption">
            &copy; 2024 Nexus Management System. All rights reserved.
        </div>
    </q-footer>

  </q-layout>
</template>

<script setup>
const features = [
    {
        icon: 'analytics',
        title: 'Advanced Analytics',
        desc: 'Deep dive into your data with our comprehensive analytics tools. Visualize growth and identify trends.'
    },
    {
        icon: 'inventory_2',
        title: 'Inventory Management',
        desc: 'Track stock levels, orders, and sales in real-time. Automated alerts for low inventory.'
    },
    {
        icon: 'people',
        title: 'Customer CRM',
        desc: 'Maintain detailed records of your customers. Improve relationships with integrated history and notes.'
    },
     {
        icon: 'payments',
        title: 'Seamless Payments',
        desc: 'Accept payments globally with our secure integrated gateway. Multiple methods supported.'
    },
     {
        icon: 'security',
        title: 'Enterprise Security',
        desc: 'Bank-grade encryption and security protocols to keep your business data safe and compliant.'
    },
     {
        icon: 'cloud_sync',
        title: 'Cloud Sync',
        desc: 'Access your data from anywhere, anytime. Automatic synchronization across all your devices.'
    }
]
</script>

<style lang="sass">
.text-transparent
    color: transparent

.bg-clip-text
    -webkit-background-clip: text
    background-clip: text

.bg-gradient-primary
    background-image: linear-gradient(to right, #fff, $primary)

.blur-effect
    filter: blur(80px)

.hero-section
  min-height: 100vh
  padding-top: 80px

.glass-card
    background: rgba(20, 20, 20, 0.6)
    backdrop-filter: blur(20px)

.feature-card
    transition: all 0.3s ease
    &:hover
        transform: translateY(-10px)
        background: #333 !important
        box-shadow: 0 10px 30px rgba(0,0,0,0.5)

.border-y-dim
    border-top: 1px solid rgba(255,255,255,0.05)
    border-bottom: 1px solid rgba(255,255,255,0.05)
    
.hover-underline
    position: relative
    &::after
        content: ''
        position: absolute
        width: 0
        height: 2px
        bottom: 5px
        left: 50%
        background-color: var(--q-primary)
        transition: all 0.3s
        transform: translateX(-50%)

    &:hover::after
         width: 80%

.hover-text-white
    transition: color 0.2s
    &:hover
        color: white !important

.letter-spacing-2
    letter-spacing: 2px

.fade-in-up
    animation: fadeInUp 0.8s ease-out forwards
    opacity: 0
    transform: translateY(20px)

@keyframes fadeInUp
    to
        opacity: 1
        transform: translateY(0)

body
  background-color: #000
</style>
