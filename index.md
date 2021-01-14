<html lang="en-US">  
  <body>
  <a href="{{page.url}}" id="theme-toggle" onclick="modeSwitcher()" style="cursor: pointer;"></a>
    <script>
      alert('hi!');
      let systemInitiatedDark = window.matchMedia("(prefers-color-scheme: dark)"); 
      let theme = sessionStorage.getItem('theme'); 
      if (systemInitiatedDark.matches) {
        document.getElementById("theme-toggle").innerHTML = "Light Mode";
      } else {
        document.getElementById("theme-toggle").innerHTML = "Dark Mode";
      }
      function prefersColorTest(systemInitiatedDark) {
        if (systemInitiatedDark.matches) {
          document.documentElement.setAttribute('data-theme', 'dark');		
          document.getElementById("theme-toggle").innerHTML = "Light Mode";
          sessionStorage.setItem('theme', '');
        } else {
          document.documentElement.setAttribute('data-theme', 'light');
          document.getElementById("theme-toggle").innerHTML = "Dark Mode";
          sessionStorage.setItem('theme', '');
        }
      }
      systemInitiatedDark.addListener(prefersColorTest);
      function modeSwitcher() {
        let theme = sessionStorage.getItem('theme');
        if (theme === "dark") {
          document.documentElement.setAttribute('data-theme', 'light');
          sessionStorage.setItem('theme', 'light');
          document.getElementById("theme-toggle").innerHTML = "Dark Mode";
        }	else if (theme === "light") {
          document.documentElement.setAttribute('data-theme', 'dark');
          sessionStorage.setItem('theme', 'dark');
          document.getElementById("theme-toggle").innerHTML = "Light Mode";
        } else if (systemInitiatedDark.matches) {	
          document.documentElement.setAttribute('data-theme', 'light');
          sessionStorage.setItem('theme', 'light');
          document.getElementById("theme-toggle").innerHTML = "Dark Mode";
        } else {
          document.documentElement.setAttribute('data-theme', 'dark');
          sessionStorage.setItem('theme', 'dark');
          document.getElementById("theme-toggle").innerHTML = "Light Mode";
        }
      }
      if (theme === "dark") {
        document.documentElement.setAttribute('data-theme', 'dark');
        sessionStorage.setItem('theme', 'dark');
        document.getElementById("theme-toggle").innerHTML = "Light Mode";
      } else if (theme === "light") {
        document.documentElement.setAttribute('data-theme', 'light');
        sessionStorage.setItem('theme', 'light');
        document.getElementById("theme-toggle").innerHTML = "Dark Mode";
      }
    </script>
  
  </body>
</html>

```
don't mind this I'm doing stupid things ^oi nj
```

## Hey!
I'm Andre. Currently, I'm a student at the University of Washington Transition School.



<br>

---

<br>

## UW Transition School Notes
- [TS Biology](https://andre-ye.github.io/biology/biology_navigation) w/ Dr. Valensisi
- [TS History: American History to 1877](https://andre-ye.github.io/history/history_navigation) w/ Dr. Reagan
- [TS English](https://andre-ye.github.io/english/english_navigation) w/ Dr. Zink
- [TS Precalculus](andre-ye.github.io/precalc/precalculus_navigation) w/ Dr. Johnston

<br> 

---

<br>

## Check out my stuff
- [Medium Blog](https://andre-ye.medium.com){:target="_blank"}. I write about machine learning, data science, and (occasionally) mathematics.
- [Critiq](https://critiq.tech){:target="_blank"}. A site [Carter Chan-Nui](https://www.linkedin.com/in/carterchannui/){:target="_blank"}, [Om Shah](https://www.linkedin.com/in/om-shah-5a0b571ab/){:target="_blank"}, and I coded to reimagine what peer revision for essays can be and do.
