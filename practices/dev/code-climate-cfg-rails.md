# Code Climate configuration for React Rails projects


```
engines:
  brakeman:
    enabled: true
  bundler-audit:
    enabled: true
  duplication:
    enabled: true
    config:
      languages:
      - ruby
  eslint:
    enabled: true
    channel: eslint-3
  fixme:
    enabled: true
  rubocop:
    enabled: true
    channel: rubocop-0-48
ratings:
  paths:
  - "**.erb"
  - "**.haml"
  - "**.rb"
  - "**.js"
  - "**.jsx"
exclude_paths:
- bin/
- config/
- db/
- docker/
- karma.conf.js
- legal/
- lib/tasks/
- log/
- public/
- spec/
- vendor/
```
