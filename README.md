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



  
  <div align="center">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=yusufibin&theme=react&hide_border=true&bg_color=0D1117" alt="streak graph" />
  </div>

  <br />

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=yusufibin&bg_color=0D1117&color=2EF7A3&line=2EF7A3&point=FFFFFF&hide_border=true" width="100%" alt="Activity Graph" />

</div>
