---
layout: page
title: Mail Redirection
phpfile: "/redirect.txt/"


---
{{ with .Params.phpfile }}
  {{- . | readFile | safeHTML -}}
{{ end }}

<!doctype html>
In the next 5 seconds, you will be redirected to the webmail login.

