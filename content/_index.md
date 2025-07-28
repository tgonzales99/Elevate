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
    
        <div style="text-align: center; margin-top: 2rem;">
          <img src="/media/groupphoto.jpg" alt="ELEVATE workshop visual" style="max-width: 100%; border-radius: 12px;" />
        </div>
        
    design:
      css_class: bg-white text-gray-900 dark:bg-gray-900 dark:text-white
      
  - block: markdown
    id: testimonials
    content:
      title: Testimonials
      text: >
        <div style="display: flex; justify-content: center; padding: 2rem 0;">
          <video autoplay loop muted playsinline 
            style="transform: scale(1.5); transform-origin: center; border-radius: 12px;">
            <source src="/media/testimonials.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </div>
    design:
      css_class: bg-gray-100

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
          image: meetingimage.jpg
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
          image: workingimage.jpg
          button:
            text: Join the next ELEVATE! Workshop
            url: /contact/
    design:
      # Section background color (CSS class)
      css_class: "bg-white dark:bg-gray-900"

  - block: markdown
    id: founder
    content:
      title: "About the Founder: McKell Purnell"
      text: >
        <img src="/media/founder-headshot.jpg" alt="Headshot" style="max-height: 200px; display: block; margin: 0 auto 1rem auto;">
        
        <div style="max-width: 700px; margin: 0 auto; text-align: center; font-size: 1.125rem; line-height: 1.6;">

          <p>McKell Purnell is a career strategist, speaker, and creator of the <strong>ELEVATE!</strong> program—designed to help professionals stop waiting and start winning their next promotion.</p>

          <p>Born in poverty in the Caribbean and now an executive in the U.S., McKell has reinvented herself four times—teacher, actuary, consultant, leader—earning her seat at the table through grit, clarity, and strategy.</p>

          <p>She’s worked at a Big 4 firm and a Fortune 100 company, coached high-potential professionals, and knows exactly how the game is played—and how to help you rise.</p>

          <p>McKell blends bold insight with real-world tools to help people lead with purpose, visibility, and power. Her message?</p>
          
          <p><strong>When you're stuck in your mind, you're stuck in your life. Promotion starts long before someone says ‘yes’—it begins the moment you see yourself differently.</strong></p>
        </div>
    design:
      css_class: bg-gray-100 text-gray-900 dark:bg-gray-900 dark:text-white

  - block: cta-card
    content:
      title: Reserve Your Spot NOW!
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: /contact/
    design:
      css_class: "bg-white"
      card:
        css_class: "bg-primary-300"
        css_style: ""

---
