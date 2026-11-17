# Microclimatic Planning & Design — Book Resources

Companion links for a booklet on microclimatic planning and design. Each resource has a permanent chapter-based ID and its own page. When a website becomes unavailable, replace the destination on that same page.

## Resource directory

### Chapter 3 · Local Climate

| ID | Topic | Stable resource page |
| --- | --- | --- |
| C03-01 | Summer and winter sun paths / Solar position | [Open C03-01](links/chapter-03/C03-01.md) |
| C03-02 | Typical uncomfortable winter and summer weather / TMY data | [Open C03-02](links/chapter-03/C03-02.md) |

## Naming convention

Resource IDs use `C##-##`:

- `C03` identifies Chapter 3.
- `01`, `02`, and subsequent numbers identify resources in their order of appearance within that chapter.
- Canonical files are stored in the matching chapter folder, such as `links/chapter-03/C03-02.md`.

Once assigned, an ID and its path should remain unchanged. Replace a failed destination inside the existing resource page rather than creating a new ID for the same purpose.

## Replace an unavailable website

1. Open the corresponding resource file.
2. Click GitHub's edit button and update the link text and URL under **Current recommended website**.
3. Update the usage notes if the replacement tool works differently or has different limitations.
4. Update the **Last updated** date and commit the change. Previous versions remain available in the file's History.

## Links to print in the booklet

Point each printed link or QR code to the resource's GitHub page, rather than directly to its external website. Updating the destination inside that file then leaves the printed entry point unchanged.

Preserve the repository name, GitHub owner name, and default branch `main` to maintain these addresses.

## Shorter URLs

For print, the preferred long-term option is a domain you own connected to GitHub Pages, with a short path for each resource, such as `https://example.org/c03/02/` (illustrative only). The domain and paths can stay the same if the hosting provider changes. The domain must be renewed and maintained.

GitHub Pages can also use its free `github.io` address. With the current owner and repository names, an illustrative address would be `https://xiaoyu-li-666.github.io/booklet-microclimatic-resources/c03/02/`.

**GitHub Pages and these example short paths are not configured or published by this repository yet.** The current working entry points are the Markdown resource pages linked above.

## Add a resource

For the next Chapter 3 resource, create `links/chapter-03/C03-03.md` using an existing page as a template and add it to the Chapter 3 table. Start another chapter with `C04-01`, `C05-01`, and so on. Never reuse an assigned ID for an unrelated resource.

## Scope

This repository manages links and brief descriptions. It does not store website mirrors or webpage backups. Before replacing a destination, check that the new resource still supports the corresponding discussion in the booklet.
