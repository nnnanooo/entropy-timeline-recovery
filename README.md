# entropy-timeline-recovery

# 🧠 DVR Forensic Recovery Tool

> Forensic-grade timeline reconstruction, entropy visualization, and binary recovery. Built for investigators, engineers, and digital archaeologists.

---

## ⚙️ Key Features

- **Modular Architecture**  
  Easily extend the tool with custom plugins for decoding, visualization, and export logic.

- **Timestamp Decoding Engine**  
  Supports multiple DVR formats and gracefully handles corrupted streams.

- **Entropy Visualization**  
  Interactive heatmap rendering of binary entropy to pinpoint video segments and anomalies.

- **Timeline Reconstruction**  
  Aligns timestamps across fragmented data; reveals gaps, overlaps, and hidden segments.

- **Session Saving & Resuming**  
  Recovery efforts can be saved and resumed—ideal for large forensic cases.

---

## 🎯 GUI Highlights

- Dark-themed interface with intuitive layout
- Drag-and-drop support for binary samples and plugin files
- Real-time feedback and error logging
- Plugin Manager for easy load/unload
- Dynamic resizing for high-res displays

---

## 🔒 Forensic Enhancements

- **Hash Exporting**: Generate MD5/SHA256 of recovered segments for report integrity  
- **Audit Logging**: Optional JSON-based action logs for traceability  
- **Plugin SDK**: Documentation and sample templates to develop your own modules  

---

## 🚀 Getting Started

### Prerequisites
- OS: Windows/Linux (x64)
- Runtime: .NET / Python (depending on build variant)
- Permissions: Administrator recommended

### Run
```bash
./dvr-tool.exe
# or
python main.py --gui
