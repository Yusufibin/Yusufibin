<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2EF7A3&center=true&vCenter=true&width=435&lines=Welcome+to+my+Digital+Universe;Full+Stack+Developer;Machine+Learning+Enthusiast;Reverse+Engineering+Passionate" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=yusufibin&color=blueviolet" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/yusufibin?style=social" alt="Followers" />
</div>

---

```rust
struct FullStackDeveloper {
    name: &'static str,
    role: &'static str,
    location: char,
    years_coding: u8,
    projects_completed: &'static str,
}

impl FullStackDeveloper {
    fn new() -> Self {
        Self {
            name: "Yusuf",
            role: "Full Stack Developer",
            location: '🌍',
            years_coding: 5,
            projects_completed: "50+", 
        }
    }

    fn current_adventures(&self) -> [(&str, &str); 4] {
        [
            ("Current", "Working on **** "),
            ("Learning", "Advanced Reverse Engineering techniques"),
            ("Looking", "To collaborate on innovative projects"),
            ("Ask me", "About Python, ML, and Reverse Engineering"),
        ]
    }

    fn tech_stack(&self) -> ([&str; 4], [&str; 3], [&str; 4]) {
        (
            ["Python ", "Bash ", "Julia ", "R "],
            ["Go ", "C/C++ ⚡", "Rust 🦀"],
            ["JavaScript ", "C# ", "Assembly ", "Java ☕"]
        )
    }

    fn specialities(&self) -> ([&str; 3], [&str; 3], [&str; 4]) {
        (
            ["Web/App Development ", "Reverse Engineering ", "Machine Learning "],
            ["VSCode", "Jupyter", "Android Studio"],
            ["TensorFlow", "PyTorch", "Flask", "Docker"]
        )
    }

    fn get_contact(&self) -> (&str, &str) {
        ("@kazu_rms", "aenir02")
    }
}

fn main() {
    let me = FullStackDeveloper::new();
    
    println!("Hello! I'm {}, a {} {}", me.name, me.role, me.location);
    println!("Contact me: {} | {}", me.get_contact().0, me.get_contact().1);
    
    let adventures = me.current_adventures();
    println!("Currently: {}", adventures[0].1);
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
