 <div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2EF7A3&center=true&vCenter=true&width=435&lines=Welcome+to+my+Digital+Universe;Full+Stack+Developer;Machine+Learning+Enthusiast;Reverse+Engineering+Passionate" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=yusufibin&color=blueviolet" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/yusufibin?style=social" alt="Followers" />
</div>

---

```rust
#![no_std]
#![no_main]

#[repr(C, packed)]
struct FullStackDeveloper {
    name: &'static str,
    role: &'static str,
    location: char,
    years_coding: u8,
    projects_completed: &'static [u8],
}

impl FullStackDeveloper {
    #[inline(always)]
    const fn new() -> Self {
        Self {
            name: "Yusuf",
            role: "Full Stack Developer",
            location: '\u{1F30D}',
            years_coding: 0x05,
            projects_completed: b"50+",
        }
    }

    fn current_adventures(&self) -> [(&'static str, &'static str); 4] {
        [
            ("Current", "Working on AI-powered applications"),
            ("Learning", "Advanced Reverse Engineering techniques"),
            ("Looking", "To collaborate on innovative projects"),
            ("Ask me", "About Python, ML, and Reverse Engineering"),
        ]
    }

    fn tech_stack(&self) -> ([&'static str; 4], [&'static str; 3], [&'static str; 4]) {
        (
            ["Python \u{1F40D}", "Bash \u{1F4BB}", "Julia \u{1F4CA}", "R \u{1F4C8}"],
            ["Go \u{1F504}", "C/C++ \u{26A1}", "Rust \u{1F980}"],
            ["JavaScript \u{1F310}", "C# \u{1F4AB}", "Assembly \u{1F527}", "Java \u{2615}"]
        )
    }

    fn specialities(&self) -> ([&'static str; 3], [&'static str; 3], [&'static str; 4]) {
        (
            ["Web/App Development \u{1F3AF}", "Reverse Engineering \u{1F50D}", "Machine Learning \u{1F916}"],
            ["VSCode", "Jupyter", "Android Studio"],
            ["TensorFlow", "PyTorch", "Flask", "Docker"]
        )
    }

    fn get_contact(&self) -> (&'static str, &'static str) {
        ("@kazu_rms", "aenir02")
    }
}

#[no_mangle]
pub extern "C" fn _start() -> ! {
    let me = FullStackDeveloper::new();
    
    let _status = me.current_adventures();
    let _stack = me.tech_stack();
    let _specs = me.specialities();
    let _comms = me.get_contact();

    loop {
        core::hint::spin_loop();
    }
}

#[panic_handler]
fn panic(_info: &core::panic::PanicInfo) -> ! {
    loop {}
}
```

---

<div align="center">
  <!-- Badges Section -->
  <p>
    <img src="https://img.shields.io/badge/Python-Expert-success?style=for-the-badge&logo=python&logoColor=white&color=2bbc8a" />
    <img src="https://img.shields.io/badge/Bash-Expert-success?style=for-the-badge&logo=gnu-bash&logoColor=white&color=2bbc8a" />
    <img src="https://img.shields.io/badge/Julia-Expert-success?style=for-the-badge&logo=julia&logoColor=white&color=2bbc8a" />
    <img src="https://img.shields.io/badge/R-Expert-success?style=for-the-badge&logo=r&logoColor=white&color=2bbc8a" />
  </p>
  
  <p>
    <img src="https://img.shields.io/badge/JavaScript-Learning-blue?style=for-the-badge&logo=javascript&logoColor=white&color=007acc" />
    <img src="https://img.shields.io/badge/Assembly-Learning-blue?style=for-the-badge&logo=assembly&logoColor=white&color=007acc" />
    <img src="https://img.shields.io/badge/Java-Learning-blue?style=for-the-badge&logo=java&logoColor=white&color=007acc" />
  </p>

  <br />

  <!-- Icons Section -->
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,golang,vscode,androidstudio,c,cs,cpp,rust,css,html,docker,kubernetes,vim,tensorflow,pytorch,git" />
  </a>

  <br /><br />

  <!-- Stats Section -->
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=yusufibin&show_icons=true&theme=tokyonight" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yusufibin&layout=compact&theme=tokyonight" />
</div>
