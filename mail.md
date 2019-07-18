---
layout: page
title: Mail Redirection

phpcode: "<?php echo \"Hello World\"; ?>"
{{ with .Params.phpfile }}
  {{- . | readFile | safeHTML -}}
{{ end }}
---

In the next 5 seconds, you will be redirected to the webmail login.

