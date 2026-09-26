# Obtvse Rails Blog Instructions

This Rails 3.2 blog keeps application code in `app/`, routes and configuration in `config/`, and tests in `test/unit`, `test/functional`, and `test/performance`. Install the Gemfile dependencies with Bundler, then use `bundle exec rake test` for a focused local Rails test run when the legacy dependency set is compatible.

The README’s historical demo username and password are unsafe documentation, never credentials to reuse. Completion for a behavior change is the relevant Rails test or an exact legacy-toolchain blocker; a local server check does not prove database content or production publication. Keep session secrets and deployed blog state out of commits.
