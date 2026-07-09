# VHome

სტატიკური საიტი, განთავსებული **Cloudflare Pages**-ზე, კოდი — **GitHub**-ზე.

## სტრუქტურა

```
.
├── index.html      # მთავარი გვერდი
├── styles.css      # სტილები
├── favicon.svg     # საიტის იკონა
└── README.md
```

## ლოკალურად ნახვა

უბრალოდ გახსენი `index.html` ბრაუზერში, ან გაუშვი მარტივი სერვერი:

```bash
npx serve .
```

## Deployment

საიტი ავტომატურად ახლდება, როგორც კი ცვლილებები აიტვირთება `main` ბრენჩზე GitHub-ზე.
Cloudflare Pages აკვირდება რეპოზიტორიას და აქვეყნებს ახალ ვერსიას.

- **Build command:** (ცარიელი)
- **Build output directory:** `/`
