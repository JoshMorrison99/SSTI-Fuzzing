# SSTI-Fuzzing
Server-side template injection is when an attacker is able to use native template syntax to inject a malicious payload into a template, which is then executed server-side.

### Summary
| Template Engine | Language | Payloads | Relevance |
|-----------------|-------------|----------|-----------|
| FreeMarker | Java | <ul><li>${7\*7}</li><li>#{7\*7}</li></ul> | 801 Stars |
| Twig | PHP| <ul><li>{{7\*7}}</li></ul> | 7.7k Stars |
| Jinja | Python | <ul><li>{{7\*7}}</li></ul> | 8.9k Stars |
| Pug | NodeJS | <ul><li>#{7\*7}</li></ul> | 21k Stars |
| Nunjucks | NodeJS | <ul><li>{{7\*7}}</li></ul> | 7.9k Stars |
| ERB | Ruby | <ul><li><%= 7*7 %></li></ul> |  |
