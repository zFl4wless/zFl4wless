### Noah here 👋

I'm a software developer and Applied Computer Science student.

Wondering what I’ve been up to lately?

---

#### See what I’m working on right now

{{range recentContributions 9}}
- [{{.Repo.Name}}]({{.Repo.URL}}) - {{.Repo.Description}} ({{humanize .OccurredAt}})
{{- end}}

---

#### Check out the latest releases I’ve helped with

{{range recentReleases 9}}
- [{{.Name}}]({{.URL}}) ([{{.LastRelease.TagName}}]({{.LastRelease.URL}}), {{humanize .LastRelease.PublishedAt}}) - {{.Description}}
{{- end}}
