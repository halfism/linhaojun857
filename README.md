### Hi 👋，I'm linhaojun857

### About me

```go
package main

import (
	"fmt"
)

type Bio map[string]interface{}

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%s: %s\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"Educational experience":    "Sophomore, Department of Computer Science and Technology, Harbin University Of Science And Technology",
		"Currently learning":        "Java Go MySQL Redis Kafka MongoDB ElasticSearch",
		"Looking to collaborate on": "Java, Golang related projects",
		"Ask me about":              "Anything related to what I am currently learning",
		"The direction of efforts":  "Be an excellent programmer and create many meaningful open source projects",
		"Personal blog":             "https://www.linhaojun.top",
	}
}
```

### GitHub Analytics

<a href="https://github.com/linhaojun857">
   <img align="" height="137px" src="https://github-readme-stats.vercel.app/api?username=linhaojun857&include_all_commits=true&count_private=true&hide_title=true&show_icons=true&include_all_commits=true&line_height=21"/>
   <img align="" height="137px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=linhaojun857&hide_title=true&layout=compact"/>
</a>
