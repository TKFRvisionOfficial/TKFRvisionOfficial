## Hi there 👋!

<!-- <img align="right" src="https://github-readme-stats.vercel.app/api?username=MarcelCoding&theme=dark"> -->
<!-- <img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarcelCoding&theme=dark"> -->

### About Me

My name is **Klemens**.
<br><br>
I'm mainly a **Python Developer**, but have experience in lot's of other languages like Java and Rust.
<br>
I'm a backend developer but mainly do parsing of easily readable data and reverse engineering of binary formats. I also like to botch apis together to make my life easier.

[![Visits](https://badges.pufler.dev/visits/TKFRvisionOfficial/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://github.com/TKFRvisionOfficial)
[![Years](https://badges.pufler.dev/years/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://github.com/TKFRvisionOfficial)
[![Repos](https://badges.pufler.dev/repos/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://github.com/TKFRvisionOfficial?tab=repositories)
[![Gists](https://badges.pufler.dev/gists/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://gist.github.com/TKFRvisionOfficial)
[![Monthly Commits](https://badges.pufler.dev/commits/monthly/TKFRvisionOfficial?style=flat-square&color=black&logo=github)](https://github.com/TKFRvisionOfficial)

### 👷 Check out what I'm currently working on
{{range recentContributions 5}}
- [{{.Repo.Name}}]({{.Repo.URL}}){{with .Repo.Description}} - {{.}}{{end}} ({{humanize .OccurredAt}})
{{- end}}

### 🌱 My latest projects
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
