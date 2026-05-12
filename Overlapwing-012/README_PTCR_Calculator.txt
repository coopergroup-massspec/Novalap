PTCR Exact-Overlap Calculator

Files
- ptcr_overlap_calculator.html : portable browser-based calculator for Windows/macOS/Linux

How to run on Windows
1. Download the HTML file.
2. Double-click it, or right-click > Open with > any modern browser.
3. Enter either:
   - Average charge Z and ± window, or
   - An explicit list of charge states
4. Click Calculate.

What it computes
- Earliest number of charge reductions that causes an exact overlap
- Guaranteed safe maximum number of reductions with no exact overlap
- Pairwise overlap thresholds
- CSV export of the pair table

Formula
For a pair of charge states z1 and z2, the first exact overlap occurs when:
- r1 = z1 / gcd(z1, z2)
- r2 = z2 / gcd(z1, z2)

The pair threshold is max(r1, r2), and the full-window safe limit is:
min(pair thresholds) - 1
