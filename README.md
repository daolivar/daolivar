<!-- Banner Image -->
<div>
    <img src="assets/macbook.jpg" alt="" width="100%" height="100%"/>
</div>

# About Me
<!-- Dropdown -->
<details>
<summary>Bio</summary>
<br>

- 👋 Hi, I’m @daolivar
- 👀 I’m interested in Software Development 💻
- 🌱 I’m currently learning:
    - <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
    - <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
    - <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
    - <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
	- <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
- 💞️ I’m looking to collaborate on open source projects big and small

</details>

# Technical Details
<!-- Dropdown -->
<details>
<summary>Go</summary>
<br>

You can run this go program ***[here](https://go.dev/play/p/Hz7w5cqChN6)***

```go
package main

import "fmt"

type David struct {
	name       string
	employer   string
	role       string
	exp        int
	edu        string
	languages  []string
	frameworks []string
	tools      []string
}

func NewDavid() *David {
	d := David{
		name:       "David Olivares",
		employer:   "Visa",
		role:       "Senior Software Engineer",
		exp:        2,
		edu:        "California State University, Monterey Bay",
		languages:  []string{"Go", "C++", "Java", "HTML", "CSS", "Javascript"},
		frameworks: []string{"React", "Bootstrap", "Xtext"},
		tools:      []string{"Bash", "Git", "Docker", "Jira", "Jenkins", "Postman", "Bitbucket"},
	}
	return &d
}

func (david *David) PrintDetails() {
	fmt.Printf("Hello, my name is %s.\n", david.name)
	fmt.Printf("I currently work at %s as a %s with approx. %d years experience.\n", david.employer, david.role, david.exp)
	fmt.Printf("I graduated from %s in May, 2020.\n", david.edu)

	fmt.Println("Programming languages I use include:")
	for _, lang := range david.languages {
		fmt.Printf("\t- %s\n", lang)
	}

	fmt.Println("Development Frameworks I am familiar with include:")
	for _, framemwork := range david.frameworks {
		fmt.Printf("\t- %s\n", framemwork)
	}

	fmt.Println("Development tools I am familiar with include:")
	for _, tool := range david.tools {
		fmt.Printf("\t- %s\n", tool)
	}
}

func main() {
	daolivar := NewDavid()
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
