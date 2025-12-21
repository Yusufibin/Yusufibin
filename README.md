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
    name: *const u8,
    role: *const u8,
    location: *const u8,
    years_coding: u32,
    projects_completed: *const u8,
}

#[no_mangle]
pub extern "C" fn _start() -> ! {
    let name_bytes = b"Yusuf\0";
    let role_bytes = b"Full Stack Developer\0";
    let loc_bytes = b"\xF0\x9F\x8C\x8D\0";
    let proj_bytes = b"50+\0";

    let _identity = FullStackDeveloper {
        name: name_bytes.as_ptr(),
        role: role_bytes.as_ptr(),
        location: loc_bytes.as_ptr(),
        years_coding: 5,
        projects_completed: proj_bytes.as_ptr(),
    };

    loop {
        unsafe {
            core::arch::asm!("nop");
        }
    }
}

#[panic_handler]
fn panic(_info: &core::panic::PanicInfo) -> ! {
    loop {}
}
```
