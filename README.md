# GP / GC dashboard

Galvanised plain coil (GP) and galvanised corrugated sheet (GC) review for
Evonith Value Steel: dispatch, NSR and BENSR, product mix, customers, branches,
the channel companies' third-party sales, and receivables.

`index.html` is the whole site. Its figures are AES-GCM encrypted and only
readable with the password, which is not kept in this repository.

Rebuild from the `dashboard scripts` folder of the working copy:

    python export_web.py
    python build_web.py --template template_v2.html --out index_v2.html
