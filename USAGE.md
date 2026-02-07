# Usage

## Run

```bash
pip install -r requirements.txt
python testbench_generator.py
```

## Typical workflow

1) **Project Details**
   - Set **Project Name**
   - Choose an **Output Directory**
   - Select a **DUT File Path** (`*.sv`)
   - Click **Save Project**

2) **Interface & DUT**
   - Click **Import from DUT**
   - Choose clock/reset (if applicable)
   - Save

3) **Transaction / Agent / (optional) Scoreboard**
   - Import/select fields and names
   - Save each page

4) **Environment / Sequence / Test / Top Module**
   - Fill required names/options
   - Save each page

5) **Preview**
   - Review generated files
   - (Optional) edit and **Save Tab Override** / **Save All Overrides**

6) **Dashboard → Generate Testbench**
   - Click **Generate Testbench**
   - The output folder is created at `<Output Directory>/<Project Name>/`

## Keyboard shortcuts

- `Ctrl+T` — Toggle theme
- `Ctrl+Q` — Exit

