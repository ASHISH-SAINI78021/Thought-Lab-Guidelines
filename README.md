<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thought Lab Quick Response Team</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #2e7d32;
      --secondary: #1565c0;
      --accent: #43a047;
      --light-bg: #f8fdf8;
      --card-bg: #ffffff;
      --text: #333333;
      --highlight: #e8f5e9;
    }
    
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #e0f7fa, #f1f8e9);
      margin: 0;
      padding: 0;
      color: var(--text);
      line-height: 1.6;
    }
    
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: var(--card-bg);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 15px 30px rgba(0,0,0,0.1);
      position: relative;
      overflow: hidden;
    }
    
    .container::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 8px;
      background: linear-gradient(90deg, var(--primary), var(--secondary));
    }
    
    h1 {
      text-align: center;
      color: var(--primary);
      font-size: 2.5em;
      margin-bottom: 30px;
      position: relative;
      padding-bottom: 15px;
    }
    
    h1::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 100px;
      height: 4px;
      background: linear-gradient(90deg, var(--primary), var(--secondary));
      border-radius: 2px;
    }
    
    h2 {
      color: var(--secondary);
      margin-top: 40px;
      padding: 10px 15px;
      border-radius: 8px;
      background-color: rgba(21, 101, 192, 0.1);
      display: inline-block;
      font-size: 1.5em;
      transform: translateX(-15px);
    }
    
    p {
      font-size: 1.1em;
      margin-bottom: 20px;
    }
    
    ul {
      list-style: none;
      padding: 0;
      margin: 25px 0;
    }
    
    ul li {
      margin: 15px 0;
      font-size: 1.1em;
      background: var(--light-bg);
      padding: 15px 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
      transition: all 0.3s ease;
      position: relative;
      overflow: hidden;
    }
    
    ul li:hover {
      transform: translateY(-3px);
      box-shadow: 0 6px 12px rgba(0,0,0,0.1);
    }
    
    ul li::before {
      content: "🌱";
      margin-right: 10px;
      font-size: 1.2em;
    }
    
    .highlight {
      background: var(--highlight);
      padding: 25px;
      margin: 30px 0;
      border-radius: 15px;
      border-left: 6px solid var(--accent);
      position: relative;
      overflow: hidden;
    }
    
    .highlight::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(45deg, transparent 65%, rgba(67, 160, 71, 0.1) 100%);
      z-index: 0;
    }
    
    .highlight h2 {
      background: none;
      padding: 0;
      margin-top: 0;
      transform: none;
    }
    
    .footer {
      text-align: center;
      margin-top: 50px;
      font-weight: 600;
      color: #555;
      padding: 20px;
      background: rgba(233, 245, 233, 0.5);
      border-radius: 10px;
      position: relative;
    }
    
    .footer::before {
      content: '⚡';
      position: absolute;
      left: 20px;
      top: 50%;
      transform: translateY(-50%);
      font-size: 1.5em;
    }
    
    .footer::after {
      content: '⚡';
      position: absolute;
      right: 20px;
      top: 50%;
      transform: translateY(-50%);
      font-size: 1.5em;
    }
    
    strong {
      color: var(--primary);
      font-weight: 600;
    }
    
    /* Animations */
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0px); }
    }
    
    .floating-icon {
      animation: float 3s ease-in-out infinite;
      display: inline-block;
    }
    
    .pulse {
      animation: pulse 2s infinite;
    }
    
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.05); }
      100% { transform: scale(1); }
    }
    
    /* Responsive */
    @media (max-width: 768px) {
      .container {
        padding: 25px;
        margin: 20px;
      }
      
      h1 {
        font-size: 2em;
      }
      
      .footer::before, .footer::after {
        display: none;
      }
    }
  </style>
</head>
<body>
  <div class="container animate__animated animate__fadeIn">
    <h1><span class="floating-icon">🌱</span> Thought Lab Quick Response Team (QRT)</h1>
    <p class="animate__animated animate__fadeIn animate__delay-1s">To strengthen our community and ensure the smooth execution of Thought Lab's activities, we are launching the <strong>Quick Response Team (QRT)</strong>.</p>
    
    <h2 class="animate__animated animate__fadeIn animate__delay-1s">🎯 Objectives</h2>
    <p class="animate__animated animate__fadeIn animate__delay-1s">The QRT will be a dynamic team of dedicated members responsible for ensuring that all initiatives of Thought Lab run efficiently and with creativity.</p>
    
    <h2 class="animate__animated animate__fadeIn animate__delay-1s">🛠️ Responsibilities</h2>
    <ul>
      <li class="animate__animated animate__fadeInUp">📢 Preparing advertisements for newspapers and social media</li>
      <li class="animate__animated animate__fadeInUp animate__delay-1s">📸 Capturing event moments through photos and videos</li>
      <li class="animate__animated animate__fadeInUp animate__delay-1s">💡 Proposing innovative ideas for club growth</li>
      <li class="animate__animated animate__fadeInUp animate__delay-2s">🎨 Designing posters, banners, and other promotional material</li>
      <li class="animate__animated animate__fadeInUp animate__delay-2s">📝 Creating Google Forms for registrations and feedback</li>
      <li class="animate__animated animate__fadeInUp animate__delay-3s">🎤 Anchoring and hosting club events</li>
      <li class="animate__animated animate__fadeInUp animate__delay-3s">👥 Managing and supporting teams during events</li>
    </ul>
    
    <h2 class="animate__animated animate__fadeIn animate__delay-2s">🏅 Points & Rewards System</h2>
    <p class="animate__animated animate__fadeIn animate__delay-2s">Each member, including the secretaries, will begin with <strong>100 points</strong>. Scores will increase or decrease based on the following factors:</p>
    <ul>
      <li class="animate__animated animate__fadeInRight">✅ Behavior with seniors & peers</li>
      <li class="animate__animated animate__fadeInRight animate__delay-1s">🧘 Meditation Score (regularity & sincerity)</li>
      <li class="animate__animated animate__fadeInRight animate__delay-1s">📆 Attendance in Thought Lab sessions</li>
      <li class="animate__animated animate__fadeInRight animate__delay-2s">📜 Certificate Contributions (extra participation in activities/events)</li>
      <li class="animate__animated animate__fadeInRight animate__delay-2s">👥 Team Score (collaboration & leadership during events)</li>
    </ul>
    
    <div class="highlight pulse animate__animated animate__fadeIn animate__delay-3s">
      <h2>🔑 Exclusive Privilege for QRT Members</h2>
      <p>All QRT members will be granted <strong>Admin Access</strong> to the official Thought Lab website <span class="floating-icon">🌐</span>. This privilege allows them to directly contribute, manage, and innovate on our club's digital platform.</p>
    </div>
    
    <h2 class="animate__animated animate__fadeIn animate__delay-3s">🏆 Monthly Rewards</h2>
    <p class="animate__animated animate__fadeIn animate__delay-3s">At the end of each month, the <strong>top 3 candidates</strong> with the highest scores will receive exciting prizes <span class="floating-icon">🎁</span>.</p>
    
    <h2 class="animate__animated animate__fadeIn animate__delay-4s">🎖️ Leadership Opportunities</h2>
    <p class="animate__animated animate__fadeIn animate__delay-4s">Final selection of <strong>future Thought Lab secretaries</strong> will be based on these scores, ensuring that only the most dedicated and impactful members rise to leadership roles.</p>
    
    <div class="footer animate__animated animate__fadeIn animate__delay-4s">
      This system ensures fair recognition, motivates members to stay active, and keeps the spirit of <strong>discipline + creativity + collaboration</strong> alive in Thought Lab.
    </div>
  </div>

  <script>
    // Add intersection observer for scroll animations
    document.addEventListener('DOMContentLoaded', function() {
      const animateElements = document.querySelectorAll('.animate__animated');
      
      const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            const animation = entry.target.getAttribute('class').match(/animate__\w+/)[0];
            entry.target.classList.add(animation);
            observer.unobserve(entry.target);
          }
        });
      }, {
        threshold: 0.1
      });
      
      animateElements.forEach(element => {
        observer.observe(element);
      });
      
      // Add hover effect to list items
      const listItems = document.querySelectorAll('li');
      listItems.forEach(item => {
        item.addEventListener('mouseenter', () => {
          item.style.transform = 'translateY(-5px)';
        });
        item.addEventListener('mouseleave', () => {
          item.style.transform = 'translateY(0)';
        });
      });
    });
  </script>
</body>
</html>