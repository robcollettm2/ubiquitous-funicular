## Application Device

The user currently installs the Metre2 software using the following:

- .NET 4.6.2
- WPF
- Clickonce

As the local hierachy is local-disk-based the Desktop / Publisher applications are the only pieces of software with access.

The WPF platform is no longer developed and so has a shelf life. Newer libraries aren't being developed.

Therefore the Microsoft UWP platform should be utilitised (along side the cloud based hiearchy) to allow us to move the estimating process along. This will mean:

- Use of newer libraries within the UWP product
- Code reuse on other platforms supported by UWP-shared libraries
- Other applications/sites could use the same 'live' hierarchy for particular tasks
  - Tablet dashboards
  - Tablet reporting
  - Tablet viewing applications
  - Keyboard-based search tool
- Managed delivery tool via the Windows Store
- Managed payment method via the Windows Store
  - Trial full version
  - Single payment covering storage costs only (no human support)
