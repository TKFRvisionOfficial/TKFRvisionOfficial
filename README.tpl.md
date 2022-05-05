## What's up 😁!

<!-- <img align="right" src="https://github-readme-stats.vercel.app/api?username=MarcelCoding&theme=dark"> -->
<!-- <img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarcelCoding&theme=dark"> -->

### About Me

My name is **Klemens**. I do things
<br><br>
I mainly do Python things. But I also do *insert language/technolagy/framework here* things.
<br>
I do binary format things, parsing things, but also API things. 

If you want to follow me on other sides just go through my [<img alt="linktree" width="20px" src="https://res.cloudinary.com/crunchbase-production/image/upload/c_lpad,f_auto,q_auto:eco,dpr_1/h90nveymaytblh5fldz8" />](https://linktr.ee/tkfrvision).

[![Visits](https://badges.pufler.dev/visits/TKFRvisionOfficial/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://github.com/TKFRvisionOfficial)
[![Years](https://badges.pufler.dev/years/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://github.com/TKFRvisionOfficial)
[![Repos](https://badges.pufler.dev/repos/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://github.com/TKFRvisionOfficial?tab=repositories)
[![Monthly Commits](https://badges.pufler.dev/commits/monthly/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://github.com/TKFRvisionOfficial)

### 😓 Check out what I'm currently struggling at
{{range recentContributions 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}){{with .Repo.Description}} - {{.}}{{end}} ({{humanize .OccurredAt}})
{{- end}}

### ☠ My latest junk
{{range recentRepos 5}}
- [{{.Name}}]({{.URL}}){{with .Description}} - {{.}}{{end}}
{{- end}}

### 🔭 Latest releases I've contributed to
{{range recentReleases 5}}
- [{{.Name}}]({{.URL}}) ([{{.LastRelease.TagName}}]({{.LastRelease.URL}}), {{humanize .LastRelease.PublishedAt}}){{with .Description}} - {{.}}{{end}}
{{- end}}

### 🔨 Latest Pull Requests I published
{{range recentPullRequests 5}}
- [{{.Title}}]({{.URL}}) on [{{.Repo.Name}}]({{.Repo.URL}}) ({{humanize .CreatedAt}})
{{- end}}

### ⭐ Recent stars
{{range recentStars 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}){{with .Repo.Description}} - {{.}}{{end}} ({{humanize .StarredAt}})
{{- end }}
