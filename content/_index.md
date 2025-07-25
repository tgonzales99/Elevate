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

          <p><em>Your Career Is Calling. Ready to Rise?</em></p>

          <p><strong>Spots are limited. Don’t wait to be chosen. Choose yourself.</strong></p>
        </div>
    design:
      css_class: bg-white text-gray-900 dark:bg-gray-900 dark:text-white

#  - block: features
#    id: features
#    content:
#      title: ELEVATE!
#      text: Program Highlights
#      items:
#        - name: Strategic Career Planning
#          icon: calendar-days
#          description: Create a personalized advancement roadmap that aligns your current role with your long-term vision.
#
#        - name: Personal Branding
#          icon: user-circle
#          description: Learn how to confidently communicate your value, stand out in your industry, and attract the right opportunities.
#
#        - name: Promotion Readiness
#          icon: star
#          description: Understand the invisible rules of promotion, and develop the presence, clarity, and language to get to the next level.
#
#        - name: Communication Power
#          icon: microphone
#          description: Master high-impact communication skills to speak with authority and authenticity—whether in meetings, reviews, or interviews.
#
#        - name: Visibility Strategy
#          icon: eye
#          description: Move from being overlooked to being recognized, with practical tactics to increase your influence and executive exposure.
#
#        - name: Mindset Shift
#          icon: sparkles
#          description: Replace self-doubt with strategic confidence so you stop waiting to be chosen and start choosing yourself.

  - block: cta-image-paragraph
#    id: solutions
    content:
      items:
        - title: 'For Professionals Who...'
          text: ""
          feature_icon: check
          features:
            - 'Are crushing it but still flying under the radar'
            - 'Want that promotion—but don’t know how to make it happen'
            - 'Are ready to lead with confidence and clarity'
            - 'Are ready to own your personal brand and stand out at work'
          # Upload image to `assets/media/` and reference the filename here
          image: elevate-web-image.png
          button:
            text: Join the next ELEVATE! Workshop
            url: /contact/
        - title: 'What You''ll Master'
          text: ""
          feature_icon: bolt
          features:
            - '<strong>Career Roadmap.</strong> Build a career plan that puts you in control.'
            - '<strong>Personal Branding.</strong> Show up. Stand out. Be unforgettable.'
            - '<strong>Promotion Playbook.</strong> Crack the code to get promoted.'
            - '<strong>Speak with Power.</strong> Say it like you mean it—and get heard.'
            - '<strong>Visibility Boost.</strong> Stop being overlooked. Start being spotlighted.'
            - '<strong>Mindset Reset.</strong> Ditch doubt. Move with purpose.'
          # Upload image to `assets/media/` and reference the filename here
          image: elevate-web-image.png
          button:
            text: Join the next ELEVATE! Workshop
            url: /contact/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"

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
