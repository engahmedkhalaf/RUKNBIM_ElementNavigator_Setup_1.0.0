# RUKNBIM Element Navigator

A Navisworks dock-pane addin for fast lookup of Revit Element IDs inside coordinated `.nwd` / `.nwc` models.

**What it does**
- Paste or import a list of Revit Element IDs → instantly **select**, **isolate**, and **zoom** to the matching elements across all loaded models.
- Reports which IDs were **found** vs **missing** and exports the result to Excel.
- One-click **Restore Full Model** to undo isolation.

**Why it's useful**
Clash reports, RFIs, and BOQ exports from Revit reference elements by ID. Manually finding 30 IDs in a federated model takes minutes per ID; this addin does the whole batch in seconds, with a built-in cache that handles million-element models.

**Features**
- Tabbed UI: Search · Results · About
- Import IDs from Excel / CSV; export found+missing report to Excel (EPPlus)
- Live status bar and per-search summary
- Auto update-check against GitHub releases
- Per-user install (`%AppData%\Autodesk\ApplicationPlugins`) — no admin rights needed

**Compatibility**
Navisworks Manage / Simulate **2024, 2025, 2026** (Nw21–Nw23), Windows x64.

**Tech**
.NET Framework 4.8 · WPF · CommunityToolkit.Mvvm · EPPlus · Inno Setup 7 installer.

**Author**
Ahmed Khalaf — BIM Manager · +966 54 255 4127 · engkhalaf7@gmail.com
[github.com/engahmedkhalaf/RUKNBIM.ElementNavigator](https://github.com/engahmedkhalaf/RUKNBIM.ElementNavigator) · [rukn-bim-website-opka.vercel.app](https://rukn-bim-website-opka.vercel.app)
