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
- 👀 I’m interested in Software Development 💻, Basketball 🏀, Spider-Man 🕷 and Pandas 🐼
- 🌱 I’m currently learning:
    - <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
    - <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
    - <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
    - <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
- 💞️ I’m looking to collaborate on open source projects big and small

</details>

# Technical Details
<!-- Dropdown -->
<details>
<summary>Go</summary>
<br>

You can run this go program __[here](https://go.dev/play/p/P1pBxLMRCn9)__

```go
package main

import "fmt"

type David struct {
	name      string
	employer  string
	role      string
	exp       int
	edu       string
	languages []string
	tools     []string
}

func CreateDavid() *David {
	d := David{
		name:      "David Olivares",
		employer:  "Visa",
		role:      "Senior Software Engineer",
		exp:       2,
		edu:       "California State University, Monterey Bay",
		languages: []string{"Go", "C++", "Java", "HTML", "CSS", "Javascript"},
		tools:     []string{"Git", "Docker", "Jira", "Jenkins", "Bootstrap", "Postman", "Chrome Dev Tools"},
	}
	return &d
}

func main() {
	daolivar := CreateDavid()
	fmt.Printf("%#v\n", daolivar)
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
