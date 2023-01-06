<!-- Banner Image -->
<div>
    <img src="assets/macbook.jpg" alt="" width="100%" height="100%"/>
</div>

<!-- socials badge imgs -->
[linkedin badge]:https://tinyurl.com/linkedin-badge
[gmail badge]:https://tinyurl.com/email-badge
[github badge]:https://tinyurl.com/github-badge

<!-- link vars -->
[linkedin profile]:https://www.linkedin.com/in/david-olivares-bbb511254
[send end click]:mailto:daveolivares01@gmail.com
[github profile]:https://github.com/daolivar

<!-- language badge imgs -->
[bash badge]:https://tinyurl.com/gnu-bash-badge
[c++ badge]:https://tinyurl.com/cpp-badge
[css badge]:https://tinyurl.com/css-badge
[html badge]:https://tinyurl.com/html-badge
[java badge]:https://tinyurl.com/java-badge
[js badge]:https://tinyurl.com/js-badge
[go badge]:https://tinyurl.com/go-badge

# About Me
<!-- Dropdown -->
<details>
<summary>Bio</summary>
<br>

- 👋 Hi, I’m @daolivar
- 👀 I’m interested in Software Development 💻
- 🔭 I’m currently working on ...
![Java][java badge] ![Go][go badge] ![C++][c++ badge]
- 🌱 I’m currently learning ...
![Bash][bash badge] ![Html][html badge] ![Css][css badge] ![Javascript][js badge]
- 🤝 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
[![LinkedIn][linkedin badge]][linkedin profile] [![Gmail][gmail badge]][send end click] [![Github][github badge]][github profile]
- ⚡ Fun fact: ...

</details>

# Technical Details
<!-- Dropdown -->
<details>
<summary>Go</summary>
<br>

You can run this go program ***[here](https://go.dev/play/p/gE1coEj4_jo)***

```go
package main

import "fmt"

type Developer struct {
	name      string
	employer  string
	role      string
	exp       int
	edu       string
	languages []string
	tools     []string
	subjects  []string
}

func NewDeveloper() *Developer {
	d := Developer{
		name:      "David Olivares",
		employer:  "Visa",
		role:      "Senior Software Engineer",
		exp:       2,
		edu:       "California State University, Monterey Bay",
		languages: []string{"Go", "C++", "Java"},
		tools:     []string{"Bash", "Git", "Docker", "Jenkins", "Postman"},
		subjects:  []string{"HTML", "CSS", "Javascript"},
	}
	return &d
}

func (dev *Developer) PrintDetails() {
	fmt.Printf("Hello, my name is %s.\n", dev.name)
	fmt.Printf("I currently work at %s as a %s with approx. %d years experience.\n", dev.employer, dev.role, dev.exp)
	fmt.Printf("I graduated from %s in May, 2020.\n", dev.edu)

	fmt.Println("Programming languages I use include:")
	for _, lang := range dev.languages {
		fmt.Printf("\t- %s\n", lang)
	}

	fmt.Println("Development tools I am familiar with include:")
	for _, tool := range dev.tools {
		fmt.Printf("\t- %s\n", tool)
	}

	fmt.Println("I am currently learning:")
	for _, subject := range dev.subjects {
		fmt.Printf("\t- %s\n", subject)
	}
}

func main() {
	daolivar := NewDeveloper()
	daolivar.PrintDetails()
}
```
</details>


## GitHub Stats
<!-- GitHub Stat cards -->
<div align="center">
	<img src="https://github-readme-stats.vercel.app/api?username=daolivar&show_icons=true&theme=react" alt="daolivar github stats" width="75%" height="75%"/>
</div>

<!-- Top Languages card clickable -->
<div align="center">
	<a href="https://github.com/daolivar?tab=repositories">
		<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=daolivar&layout=compact&langs_count=7&theme=react" width="75%" height="75%"/>
	</a>
</div>

<!-- Spider Cat 'Hidden' Dropdown -->
<div align="center">
	<details>
	<summary></summary>
	<br>
		<img src="assets/spidertocat.png" alt="spider-cat" width="50%" height="50%"/>
	</details>
</div>
