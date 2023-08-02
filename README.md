  # My Portfolio

## Introduction
<div style="background-image: url('./Assets/background_image.jpg'); background-size: cover; padding: 100px 0; text-align: center; color: white;">
  <h2>Hi, I'm Mary, a developer. Welcome to my portfolio!</h2>
  <img src="./Assets/profile_picture_adjusted.png" alt="Profile Picture">
  <blockquote>
    “My powers are ordinary. Only my application brings me success.” ~ Isaac Newton
  </blockquote>
  <a href="https://www.instagram.com/learnwlala/">
    <img src="./Assets/instagram.png" alt="Instagram">
  </a>
  <a href="https://www.linkedin.com/in/mary-narainsamy-294bb0102/">
    <img src="./Assets/linkedin.png" alt="LinkedIn">
  </a>
</div>

---

## Experience
<div style="display: grid; grid-template-columns: 1fr 1fr; grid-gap: 20px;">
  <div>
    <h3>Custom Development</h3>
    <ul>
      <li>Maintaining system code</li>
      <li>Web development</li>
      <li>Documentation</li>
      <li>Building custom applications</li>
      <li>Languages: React.js, JavaScript, C#</li>
    </ul>
  </div>
  <div>
    <h3>Power Platform Developer</h3>
    <ul>
      <li>Building Business Apps</li>
      <li>Automating Processes with Power Automate</li>
      <li>Integrating external systems with Adaptive Cards (Binder/AIDL)</li>
      <li>Languages: Power FX, Javascript, C#</li>
    </ul>
  </div>
  <div>
    <h3>CRM Developer</h3>
    <ul>
      <li>Dynamics 365 Developer</li>
      <li>Maintaining Dynamics CRM</li>
      <li>Languages: JavaScript, C#</li>
    </ul>
  </div>
  <div>
    <h3>Tutorials & Development</h3>
    <ul>
      <li>YouTube Tutorials</li>
      <li>Freelance App Dev</li>
    </ul>
  </div>
</div>

---

## Projects
<div style="display: grid; grid-template-columns: 1fr 1fr; grid-gap: 20px;">
  <div>
    <h3>Power Automate Project</h3>
    <img src="./src/Components/Assets/Project2Image.png" alt="Project 2">
    <p>Built Helpdesk using Power Automate, Adaptive Cards, and Teams</p>
    <ul>
      <li>Built Helpdesk using Power Automate, Adaptive Cards, and Teams</li>
      <li>Multiple workflows for automation</li>
    </ul>
  </div>
  <div>
    <h3>Custom Projects</h3>
    <img src={project3Image} alt="Project 3" className="project-image" />
    <ul>
      <li>Built a console App that runs on a daily basis and checks the all user access then stores file in blob storage, to be used for fire drill when necessary.</li>
      <li>The app interface was created in PowerApps, backend was coded as a console app using C# and run daily.</li>
      <li>Other projects include, my portfolio is developed using React.js</li>
    </ul>
  </div>
  <div>
    <h3>Project 4</h3>
    <img src={project4Image} alt="Project 4" className="project-image" />
    <ul>
      <li>My youtube channel Learn with Lala is just at the beginning of its youtube journey.</li>
      <li>Currently working on my Youtube channel providing tutorials on the Power Platform.</li>
      <li>Tutorials on Adaptive cards and other uses for it.</li>
      <li>Currently under construction, pending more video tutorials.</li>
    </ul>
  </div>
</div>

---

## Contact Me
Please feel free to get in touch for a consultation. If you have questions regarding PowerApps/Power Automate, Adaptive cards, etc.

**Name**
<input type="text" name="user_name" required>

**Email**
<input type="email" name="user_email" required>

**Message**
<textarea name="message" rows="4" required></textarea>

**Contact Number**
<input type="tel" name="contact_number" pattern="[0-9]{10}" required>

**Company?**
<input type="text" name="company_name">

**Select Option you would like to partner with us for:**
<select name="solution_option">
  <option value="PowerApps/Power Automate">PowerApps/Power Automate</option>
  <option value="Custom Development">Custom Development</option>
  <option value="Consultation">Consultation</option>
  <option value="Other">Other</option>
</select>

<button type="submit" style="height: 50px; margin-top: 10px;">Send</button>

