---
layout: post
title: Production Backend Service Checklist
tags:
  # - test
  # - tags
---
Here's a checklist when setting up a new backend service in production.
- Config \\
  Where will the secrets be stored? \\
  Will it be stored together with the code? \\
  Is it under version control?
- Logger \\
  Is there log rotate set up? Will the machine run out of space?
- Process Manager \\
  What happens if the service crash? Will a new process automatically start?