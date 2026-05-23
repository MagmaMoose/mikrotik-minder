# CHANGELOG

<!-- version list -->

## v1.4.0 (2026-05-23)

### Bug Fixes

- **admin**: Add anti-caching headers to artifact download endpoint
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **admin**: Derive requested_by from authenticated user instead of request body
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **admin**: Make artifact download atomic with UPDATE ... RETURNING
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **admin**: Populate requested_by from X-Auth-Email header
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **admin**: Return pre-update artifact in one-shot download endpoint
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **admin**: Validate X-Auth-Email header for commands endpoint
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **agent**: Align sensitive export docstring with CRLF normalization
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **agent**: Enforce artifact size limit in sensitive export command
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **agent**: Report command results for export/backup commands
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **agent**: Satisfy ruff (unused noqa + line length)
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **agent**: Wrap E501 in sensitive export size-limit message
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **agent**: Wrap long MinderError lines added by status_code refactor
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **daemon**: Accept CommandRef in _execute_command_via_daemon
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **daemon**: Update device timestamps after command execution
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **ingest**: Fix invalid SQL in command claim query
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **ingest**: Preserve artifact payload verbatim without trimming
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **worker**: Guard JSON.parse of command params in poll endpoint
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **worker**: Null-check artifact before returning the download body
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **worker**: Reject arrays in command result validation
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **worker**: Restore SLACK_INFO_CHANNEL dropped in the #13 merge
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **worker**: Return 202 for pending/claimed commands on artifact endpoint
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

### Chores

- **chart**: Mikrotik-minder-agent 0.1.3 (appVersion 0.0.2)
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

### Features

- **agent**: Poll for operator-triggered commands and execute them
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **worker**: Command-dispatch endpoints + commands table
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **worker**: Command-dispatch foundation (commands table + endpoints)
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

### Performance Improvements

- **ingest**: Eliminate N+1 query in GET /commands by joining device name
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **worker**: Add composite index for command claim query
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

### Refactoring

- **db**: Remove redundant commands_agent_idx index
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))

- **minder**: Include HTTP status code in MinderError for robust 404 handling
  ([#15](https://github.com/MagmaMoose/mikrotik-minder/pull/15),
  [`6b0c86d`](https://github.com/MagmaMoose/mikrotik-minder/commit/6b0c86d60a87fac92c827b78893f0e58e1b28f48))


## v1.3.0 (2026-05-22)

### Bug Fixes

- **worker**: Align Slack env doc with severity-based routing
  ([`b504eef`](https://github.com/MagmaMoose/mikrotik-minder/commit/b504eef14c3225c8d33ebb160623c560a0dda154))

### Documentation

- **agent-protocol**: Clarify alert_deliveries scope for Slack bot
  ([`d7b0367`](https://github.com/MagmaMoose/mikrotik-minder/commit/d7b0367d232dd29cbf78be81b2a08abf7f1bc6ec))

- **agent-protocol**: Fix Slack bot env var table to match implementation
  ([`33c4e3f`](https://github.com/MagmaMoose/mikrotik-minder/commit/33c4e3f5dde440324cfdd5f0ba4edea698ff2c99))

### Features

- **worker**: Route Slack alerts to 3 channels by kind + announce wins
  ([`e81a81b`](https://github.com/MagmaMoose/mikrotik-minder/commit/e81a81b953392934356633e726a746e7b55ab100))

- **worker**: Slack bot-token alert delivery
  ([`08d06c3`](https://github.com/MagmaMoose/mikrotik-minder/commit/08d06c3e254a29ea1de18e04fbc0733f88093155))


## v1.2.1 (2026-05-22)

### Bug Fixes

- **chart**: Keep the git deploy key's trailing newline
  ([`073f16e`](https://github.com/MagmaMoose/mikrotik-minder/commit/073f16ef11e2ee3b84418501596f582976734f86))


## v1.2.0 (2026-05-21)

### Bug Fixes

- **agent**: Default serviceAccountName to 'default' when create is false
  ([`dc74c81`](https://github.com/MagmaMoose/mikrotik-minder/commit/dc74c81b3cc5ac77b1a90d8569188b487c6ff4f2))

### Features

- Bump agent to 0.0.1 + restore chart's image/secret helpers
  ([`8d72c7d`](https://github.com/MagmaMoose/mikrotik-minder/commit/8d72c7d20834d1ed267b33aae3e9c29a88baccb4))


## v1.1.1 (2026-05-21)

### Bug Fixes

- Complete env.prod wrangler config + opt deploy into prod environment
  ([`118bfb9`](https://github.com/MagmaMoose/mikrotik-minder/commit/118bfb94703437c25dd3134ea84f93b7976a1ddf))


## v1.1.0 (2026-05-21)

### Bug Fixes

- Address review feedback on secrets, prod env isolation, wrangler pin
  ([`ca22381`](https://github.com/MagmaMoose/mikrotik-minder/commit/ca22381d4756742e1d052e071606e592cde38a20))


## v1.0.0 (2026-05-21)

### Bug Fixes

- Address PR #3 CodeQL findings and Copilot review comments
  ([`5a1cf24`](https://github.com/MagmaMoose/mikrotik-minder/commit/5a1cf2470cb6de057bf7e79b18282e2864e71834))

### Features

- MVP scaffold — worker, agent, Helm chart, real-router validation
  ([`945f615`](https://github.com/MagmaMoose/mikrotik-minder/commit/945f6157ef0b7c9ae343f48b00366de4a330bac6))


## v0.0.1 (2026-05-19)

- Initial Release
