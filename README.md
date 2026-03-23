<div class="tierlist">
  <style>
    .tierlist {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      max-width: 800px;
      margin: 0 auto;
    }
    
    .tier-row {
      display: flex;
      margin-bottom: 8px;
      border-radius: 8px;
      overflow: hidden;
      box-shadow: 0 1px 3px rgba(0,0,0,0.1);
    }
    
    .tier-label {
      width: 80px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
      font-size: 32px;
      color: white;
      text-shadow: 0 1px 2px rgba(0,0,0,0.2);
    }
    
    .tier-s .tier-label { background: linear-gradient(135deg, #ffd700, #ffb347); }
    .tier-a .tier-label { background: linear-gradient(135deg, #c0c0c0, #a0a0a0); }
    .tier-b .tier-label { background: linear-gradient(135deg, #cd7f32, #b87333); }
    .tier-c .tier-label { background: linear-gradient(135deg, #6c757d, #5a6268); }
    .tier-d .tier-label { background: linear-gradient(135deg, #dc3545, #c82333); }
    
    .tier-content {
      flex: 1;
      background: #f8f9fa;
      padding: 12px 16px;
    }
    
    .project {
      padding: 8px 0;
      border-bottom: 1px solid #e9ecef;
    }
    
    .project:last-child {
      border-bottom: none;
    }
    
    .project-name {
      font-weight: 600;
      font-size: 16px;
      color: #1a1a2e;
      margin-bottom: 4px;
    }
    
    .project-desc {
      font-size: 13px;
      color: #6c757d;
      margin-bottom: 6px;
    }
    
    .project-url {
      font-size: 12px;
      font-family: 'SF Mono', Monaco, monospace;
    }
    
    .project-url a {
      color: #0366d6;
      text-decoration: none;
    }
    
    .project-url a:hover {
      text-decoration: underline;
    }
  </style>

  <div class="tier-row tier-s">
    <div class="tier-label">S</div>
    <div class="tier-content">
      <div class="project">
        <div class="project-name">React From Scratch</div>
        <div class="project-desc">React reimplementation with VDOM + hooks</div>
        <div class="project-url"><a href="https://github.com/username/react-from-scratch">github.com/username/react-from-scratch</a></div>
      </div>
    </div>
  </div>

  <div class="tier-row tier-a">
    <div class="tier-label">A</div>
    <div class="tier-content">
      <div class="project">
        <div class="project-name">Rust Systems</div>
        <div class="project-desc">Small Rust demos for systems topics</div>
        <div class="project-url"><a href="https://github.com/username/rust-systems">github.com/username/rust-systems</a></div>
      </div>
      <div class="project">
        <div class="project-name">React Locator</div>
        <div class="project-desc">Inspect components and jump to source</div>
        <div class="project-url"><a href="https://github.com/username/react-locator">github.com/username/react-locator</a></div>
      </div>
    </div>
  </div>

  <div class="tier-row tier-b">
    <div class="tier-label">B</div>
    <div class="tier-content">
      <div class="project">
        <div class="project-name">SSH Portfolio</div>
        <div class="project-desc">Terminal portfolio browsable over SSH</div>
        <div class="project-url"><a href="https://github.com/username/ssh-portfolio">github.com/username/ssh-portfolio</a></div>
      </div>
      <div class="project">
        <div class="project-name">Personal Site</div>
        <div class="project-desc">My website for projects and writing</div>
        <div class="project-url"><a href="https://github.com/username/personal-site">github.com/username/personal-site</a></div>
      </div>
    </div>
  </div>

  <div class="tier-row tier-c">
    <div class="tier-label">C</div>
    <div class="tier-content">
      <div class="project">
        <div class="project-name">Claude Code Clone</div>
        <div class="project-desc">CLI coding agent clone experiment</div>
        <div class="project-url"><a href="https://github.com/username/claude-clone">github.com/username/claude-clone</a></div>
      </div>
      <div class="project">
        <div class="project-name">Advent of Code 2025</div>
        <div class="project-desc">Mostly completed AoC 2025 in Python/Rust</div>
        <div class="project-url"><a href="https://github.com/username/advent-2025">github.com/username/advent-2025</a></div>
      </div>
    </div>
  </div>

  <div class="tier-row tier-d">
    <div class="tier-label">D</div>
    <div class="tier-content">
      <div class="project">
        <div class="project-name">Reading List</div>
        <div class="project-desc">Saved technical articles in one place</div>
        <div class="project-url"><a href="https://github.com/username/reading-list">github.com/username/reading-list</a></div>
      </div>
    </div>
  </div>
</div>