---
title: 'Home'
date: 2025-06-23
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Empower your career with ELEVATE!
      text: >
        <div style="text-align: center;">
          🌟Tired of being overlooked for promotions?<br>
          🌟<em>Get the step-by-step career plan to move up on your terms</em>
        </div>
      image: SVG-elevate-logo-new.svg
      primary_action:
        text: I'm Ready to ELEVATE!
        url: /contact/
        icon: arrow-right
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark text-white bg-cover bg-center text-2xl md:text-2xl"
      background:
        color: "#00A86B" # Jade Background
        image:
          # Add your image background to `assets/media/`.
          filename: SVG hexagon-image.svg
          style: "background-size: 50%; background-position: center; background-repeat: no-repeat;"
          filters:
            brightness: 0.5
 
  - block: markdown
    id: program
    content:
      title: "What is ELEVATE?"
      text: >
      
        <div style="max-width: 700px; margin: 0 auto; text-align: center; font-size: 1.125rem; line-height: 1.6;">

          <p>ELEVATE! is a 1-day interactive workshop to help you lead, brand, and ask for the promotion you deserve.</p>

          <p>No fluff. Just action.</p>

          <p><em>Your Career Is Calling. Ready to Rise?<em/></p>

          <p><strong>Spots are limited. Don’t wait to be chosen. Choose yourself.</strong></p>
        </div>
    design:
      css_class: bg-gray-100 text-gray-900 dark:bg-gray-900 dark:text-white
      
  - block: cta-image-paragraph
    content:
      items:
        - title: '<span style="color:#141436;">The NGU Approach</span>'
          text: '<span style="color:#4d4d4d;">Never Give Up Transitional Living creates a supportive space where individuals with lived experiences (i.e., previously incarcerated) serve as mentors, helping participants navigate challenges related to addiction, antisocial thinking patterns, employment, and prosocial and community reintegration.<br><br>By offering structured support, the program seeks to empower participants to rebuild their lives and achieve long-term stability.<br><br>Core elements of the program include:</span>'
          feature_icon: bolt
          features:
            - '<span style="color:#36454F;">84 days of programming</span>'
            - '<span style="color:#36454F;">24/7 supervision and accountability</span>'
            - '<span style="color:#36454F;">Stable housing</span>'
            - '<span style="color:#36454F;">Commitment to sobriety and recovery support</span>'
            - '<span style="color:#36454F;">Employment and workforce development</span>'
            - '<span style="color:#36454F;">Therapy and life skills development</span>'
            - '<span style="color:#36454F;">Family, prosocial peers, and community network (re)development</span>'
          image: GroupPhoto_2.jpg
          button:
            text: Program Overview (PDF)
            url: /docs/NGUProgramDescription.pdf
        - title: '<span style="color:#141436;">What Makes NGU Unique?</span>'
          text: '<span style="color:#4d4d4d;">Rooted in experience. Driven by hope.</span>'
          feature_icon: bolt
          features:
            - '<span style="color:#36454F;"><strong>Built for real change.</strong> Helping people rebuild lives -- not just get by.</span>'
            - '<span style="color:#36454F;"><strong>Out-of-the-box.</strong> Innovative methods tailored for lasting impact.</span>'
            - '<span style="color:#36454F;"><strong>We''ve been there.</strong> Our staff have done time, and changed their lives.</span>'
            - '<span style="color:#36454F;"><strong>We don''t give up.</strong> No matter your past, we believe in your future.</span>'
          image: groupphoto1.jpeg
          button:
            text: Meet the NGU Team
            url: /people
            style: "background-color: #FECA1B; color: #0E2240; font-weight: 700; display: block; margin: 0 auto;"
#        - title: Community (Re)Integration
#          text: Our program is supported by a broad network that includes community organizations, employers, and strong partnerships with the criminal justice system.
#          feature_icon: bolt
#          features:
#            - "Connections to local community organizations and universities"
#            - "Partnerships with employers offering job opportunities"
#            - "Collaborative support from parole officers"
#          image: HockeyPhoto.jpeg
#          button:
#            text: Join Discord
#            url: https://discord.gg/z8wNYzb
    design:
      css_class: "bg-[#FFFFFF]"
  
  - block: testimonials
    id: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "David K."
          role: "Operations Lead"
          text: "ELEVATE! gave me a framework I didn’t even know I needed. It connected the dots between how I show up, what I’m known for, and what I want next. I’m no longer just doing my job—I’m building my brand."
        - name: "Maria S."
          role: "Finance Analyst"
          text: "This program shifted my mindset completely. I used to wait for someone to ‘notice’ me. Now, I know how to position myself, speak up, and own my growth. It’s honestly the best investment I’ve made in my career."
        - name: "John R."
          role: "Finance Analyst"
          text: "Before ELEVATE!, I was working hard but feeling overlooked. Victory helped me realize I wasn’t invisible—I just wasn’t visible in the right ways. I finally know how to talk about my value without feeling like I’m bragging. Two months after the program, I got promoted."
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
 
  - block: cta-card
    content:
      title: Schedule Your Job Promotion NOW!
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: /contact/
    design:
      background:
        color: "#2C8EB3"
---
