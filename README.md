# NovelKit

A beautiful, feature-rich writing workspace for crafting novels and long-form narratives. NovelKit provides writers with an intuitive interface to manage story structure, characters, worldbuilding, and manuscript progress—all in one distraction-free environment.

## ✨ Features

### 📚 Novel Management
- Create and manage multiple novels simultaneously in your workspace
- Store and edit novel metadata including title, genre, and completion status
- Track writing progress with real-time statistics dashboard
- Import/export complete workspace backups as JSON for data persistence
- Drag-and-drop JSON file import for easy recovery
- Switch between novels instantly with single-click navigation

### ✍️ Writing & Chapters
- **Dedicated Writing Mode**: Full-screen distraction-free editor optimized for focus
- Organize your manuscript into chapters with titles and descriptions
- Track chapter status across three states: Planned → Drafting → Done
- **Live word count tracking** for individual chapters and full manuscript
- Quick chapter navigation sidebar for instant chapter selection
- Chapter status cycling with visual status badges
- Automatic content saving to browser local storage

### 🎭 Characters
- Comprehensive character profile system for story development
- Create detailed character profiles with descriptions and notes
- Color-coded character avatars (Gold, Blue, Red, Green) for visual organization
- Manage character relationships and story roles
- Character count statistics in overview dashboard

### 📖 Plot & Structure
- **Narrative framework builder** using custom acts and story structure
- Organize plot points and story clues within structured acts
- Build story progression with numbered act blocks
- Track important story beats and plot devices
- Flexible act management (add, edit, delete custom acts)
- Clue and plot point tracking within each act

### 🌍 Worldbuilding
- **Comprehensive world documentation system** for immersive storytelling
- Lore and setting documentation with unlimited detail capacity
- Store world history, rules, aesthetics, and unique details
- **Location database** for specific place descriptions and references
- Create and organize world locations with descriptions
- Reference your world details seamlessly while writing

### 📋 Story Planning
- **Story Premise Card** with multiple planning fields:
  - One-line summary of your novel's core concept
  - Themes and tone documentation
  - Full synopsis for complete story overview
  - General notes and brainstorming space
- **Planning & Schedule tracking**:
  - Target word count goal setting
  - Deadline and milestone tracking
  - Visual progress monitoring

### 📊 Overview Dashboard
- **Real-time statistics** showing:
  - Total chapters count
  - Completed chapters counter
  - Character count
  - Total words written (across all chapters)
- Statistics update automatically as you write and edit
- Quick access to all story premise information

### 💾 Data Management
- **Auto-save to browser local storage** - never lose work between sessions
- Export manuscript as **plain text (.txt)** for sharing, printing, or distribution
- Export entire workspace as **JSON backup (.json)** for complete data preservation
- Import backups anytime to restore your work
- Drag-and-drop JSON import support for convenience
- File sanitization for safe export naming

### 🎨 UI & UX Features
- **Beautiful dark theme** with warm gold accents for extended writing sessions
- Responsive sidebar navigation for easy feature access
- Modal dialogs for intuitive novel creation and settings
- **10 genre options**: Thriller, Fantasy, Sci-Fi, Mystery, Romance, Historical, Horror, Nonfiction, Adventure/Action, Dystopian
- **Focus mode** to hide sidebar and minimize distractions (maximizes writing space)
- Smooth transitions and polished interactions throughout
- Responsive design that works across devices
- Keyboard-friendly navigation and shortcuts
- Accessibility-focused UI components

### 🔄 Novel Status Workflow
- **In progress**: Currently working on the manuscript
- **Completed Blueprint**: Story structure and planning complete
- **Drafting Phase**: Initial manuscript draft in progress
- **Editing Workflow**: Revision and editing phase
- **On Hold**: Project temporarily paused
- Click to cycle through statuses instantly

## 🚀 Getting Started

### Installation
1. **Clone or download** the repository
2. **Open the Application**: Simply open `index.html` in your web browser (no installation needed!)
3. Begin writing immediately - no setup required

### First Novel Workflow
1. Click the **"New novel"** button in the sidebar
2. Enter your novel title
3. Select your story's **primary genre** from 10 options
4. Start building your story:
   - **Overview**: Add premise, themes, synopsis, and planning info
   - **Write**: Draft your chapters in distraction-free mode
   - **Chapters**: View and organize chapter structure
   - **Characters**: Create character profiles
   - **Plot**: Build narrative structure with acts
   - **World**: Document your setting and locations

## 📂 File Structure

```
NovelKit/
├── index.html          # Complete standalone application
│                       # (HTML + CSS + JavaScript bundled)
└── README.md          # Documentation (this file)
```

**Single File Architecture**: NovelKit is a self-contained single HTML file with embedded CSS and JavaScript—no build process, dependencies, or configuration needed.

## 💡 Usage Tips

### Sidebar Navigation
| Tab | Purpose |
|-----|---------|
| **Novels** | List of all projects; click to switch between them |
| **Overview** | Dashboard with statistics and story premise details |
| **Write** | Full-screen writing editor with chapter navigation |
| **Chapters** | View, organize, and manage all manuscript chapters |
| **Characters** | Create and maintain character profiles and details |
| **Plot** | Develop narrative structure using acts and plot points |
| **World** | Build and reference setting, lore, and locations |

### Chapters Tab Workflow
- Click **"Insert brand new chapter row"** to add chapters to your outline
- Click chapter titles to rename them
- Click status badges (Planned/Drafting/Done) to cycle chapter status
- Use action buttons to edit in writer mode or delete chapters
- Drag to reorder chapters (if supported)

### Write Tab Essentials
- Select a chapter from the **left sidebar** to open it for writing
- Edit **chapter title** at the top with live preview
- **Word count badge** updates in real-time as you type
- Click **status badge** to quickly change chapter status while writing
- All content **auto-saves** to local storage as you work
- Press **Escape** (if implemented) to return to chapter list

### Export & Backup Options
| Export Type | Format | Use Case |
|-------------|--------|----------|
| **Manuscript** | Plain Text (.txt) | Sharing, printing, distribution, or reading offline |
| **Backup** | JSON (.json) | Complete data preservation for recovery or migration |

### Focus Mode
- Enable **focus mode** to hide the sidebar and UI chrome
- Maximizes screen space for uninterrupted writing
- Perfect for NaNoWiMo sessions or sprint writing
- Disable to return to full feature access

## 💾 Data Storage & Privacy

**Local Storage Architecture**: NovelKit stores all your data in your browser's local storage. 

### Key Points
- ✅ **Your data never leaves your device** - no server uploads
- ✅ **Completely offline-capable** - works without internet
- ✅ **Instant saving** - automatic persistence
- ⚠️ **Clearing browser data deletes work** - use export regularly to backup

### Best Practices
- **Export regularly** to create JSON backups of your work
- Keep backups in **cloud storage** (Google Drive, Dropbox, etc.) for safety
- Test your import workflow before you need to rely on it
- Consider exporting after significant writing sessions

## 🎨 Customization

The application uses **CSS custom properties** for easy theme customization. Edit the `:root` variables in the `<style>` section to change colors:

```css
:root {
  /* Background Colors */
  --bg: #0f0e0c;              /* Primary background */
  --bg2: #1a1916;             /* Secondary background */
  --bg3: #242220;             /* Tertiary background */
  --bg4: #2e2c29;             /* Quaternary background */

  /* Text Colors */
  --text: #f0ede8;            /* Primary text */
  --text2: #9a9690;           /* Secondary text */
  --text3: #5a5752;           /* Tertiary text (labels) */

  /* Accent Colors */
  --accent: #c9a96e;          /* Primary accent (gold) */
  --accent2: #e8c98a;         /* Secondary accent (lighter gold) */

  /* Status Colors */
  --red: #c06060;             /* Delete/danger */
  --green: #6a9e6a;           /* Done/complete */
  --blue: #6a8eae;            /* Drafting state */

  /* Borders & Spacing */
  --radius: 10px;             /* Standard border radius */
  --radius-lg: 14px;          /* Large border radius */
}
```

### Color Schemes
- **Dark Mode** (default): Optimized for extended writing sessions, reduces eye strain
- **Custom Themes**: Modify CSS variables to create light mode or custom color schemes
- **Accessibility**: High contrast ratios for readability

## 📱 Browser Compatibility

Works best in modern browsers with ES6+ support:
- ✅ Chrome/Edge (recommended) - version 60+
- ✅ Firefox - version 55+
- ✅ Safari - version 10.1+
- ✅ Any Chromium-based browser
- ⚠️ IE11 not supported (uses modern JavaScript)

### Browser Storage Requirements
- Ensure **local storage is enabled** (usually enabled by default)
- Private/incognito mode: Works but data deleted when you close the window
- Recommended: Use normal mode for persistent data storage

## ⌨️ Keyboard & Navigation

- **Tab Navigation**: Use sidebar nav items to switch between views
- **Status Cycling**: Click status badges to cycle through states
- **Modal Navigation**: Use keyboard-friendly buttons to submit or cancel
- **Text Selection**: Standard copy/paste/select operations supported
- **Auto-save**: All changes saved instantly while typing

## 📝 Advanced Features Detail

### Novel Status States (Complete Workflow)
```
In progress ──→ Completed Blueprint ──→ Drafting Phase ──→ Editing Workflow ──→ On Hold
```

### Chapter Status States
```
Planned ──→ Drafting ──→ Done
```

### Word Count Calculation
- Counts actual words (whitespace-separated tokens)
- Ignores excess whitespace normalization
- Updates in real-time as you type
- Displays in human-readable format (e.g., "42,000 words")

### Data Persistence Logic
- Saves to local storage after every keystroke (debounced for performance)
- Full state snapshot on every save
- Recoverable from any save point via JSON export
- No automatic cloud sync (intentional for privacy)

## 🔒 Privacy & Security

**NovelKit respects your privacy completely**:

- ✅ **No data collection**: Zero tracking or analytics
- ✅ **No external requests**: All processing happens locally
- ✅ **No account required**: Anonymous, login-free operation
- ✅ **No ads**: Clean, distraction-free interface
- ✅ **No telemetry**: Your writing stays private
- ✅ **Open source**: Code is transparent and reviewable

## 🐛 Troubleshooting

### Lost Work
**Issue**: Can't find my work after closing the browser
- **Solution**: Check if you have a JSON backup file. Import it via "Import Backup" button in the sidebar
- **Prevention**: Export JSON backups after major milestones

### App Not Saving
**Issue**: Changes not persisting between sessions
- **Check**: Browser local storage is enabled in settings
- **Try**: Open DevTools (F12) → Application → Local Storage → check `novelkit_data` exists
- **Solution**: Some privacy browsers block storage—try disabling privacy mode

### Can't Import Backup
**Issue**: Getting error when importing JSON file
- **Verify**: File was exported from NovelKit (check for `novels` array in JSON)
- **Check**: File is valid JSON (not corrupted or edited)
- **Try**: Reimport the original backup file

### Browser Crashing
**Issue**: App becomes slow or unresponsive with large manuscripts
- **Cause**: Very large novel with many chapters in local storage
- **Solution**: Export your work and start a new project
- **Tip**: Consider splitting very large novels into separate projects

### Missing Data in Imported Backup
**Issue**: Imported backup but some data is missing
- **Cause**: Backup file is from old version or partially corrupted
- **Check**: All expected fields present in JSON structure
- **Solution**: Contact support or manually reconstruct lost data

## 📖 Tips for Writers

### Organization Best Practices
- **One novel per project**: Create separate projects for different manuscripts
- **Descriptive chapter titles**: Use meaningful names for easy navigation
- **Regular exports**: Backup your work weekly to cloud storage
- **Character tagging**: Use character names or codes in plot notes for easy searching

### Writing Workflow
1. **Planning Phase**: Develop premise, characters, and plot in Overview tab
2. **Outlining**: Create chapter structure in Chapters tab
3. **First Draft**: Write chapters in Write tab, update status as you progress
4. **Revision**: Use notes to track edits, update status to "Editing Workflow"
5. **Final Pass**: Polish and prepare for export
6. **Export & Share**: Export as .txt for agents, publishers, or readers

### Focus Writing Sessions
- Enable focus mode for distraction-free writing
- Set a timer for sprint sessions (25-50 minutes)
- Turn off notifications and close other tabs
- Use the word count badge to track daily goals

## 🎯 Roadmap & Future Features

Potential enhancements:
- Cloud sync (optional)
- Search and find functionality
- Chapter reordering via drag-and-drop
- Scene-level organization
- Revision tracking and change history
- Character relationship mapping
- Timeline visualization
- Writing statistics and analytics
- Dark mode/light mode toggle
- Mobile app version

## 📄 License

NovelKit is free and open for personal use. Feel free to modify, fork, and distribute as needed.

### Usage Rights
- ✅ Personal writing projects
- ✅ Educational purposes
- ✅ Modification and customization
- ✅ Distribution and sharing
- ✅ Commercial projects

---

## 🌟 Support & Feedback

Found a bug? Have a feature request? Visit the [Issues](https://github.com/GeorgeTW6060/NovelKit/issues) page.

---

**Happy Writing!** 📖✨

Start crafting your masterpiece today with NovelKit. Your imagination is the only limit.

*NovelKit: Where writers meet their stories.*
