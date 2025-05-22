---
title: Home
layout: home
---




[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate




# Callouts
{: .d-inline-block }

New (v0.4.0)
{: .label .label-green }

Markdown does not include support for callouts. However, you can style text as a callout using a Markdown extension supported by kramdown: [*block IALs*](https://kramdown.gettalong.org/quickref.html#block-attributes).

Common kinds of callouts include `highlight`, `important`, `new`, `note`, and `warning`.

{: .warning }
These callout names are *not* pre-defined by the theme: you need to define your own names.



[^postfix]:
    You can put the callout markup either before or after its content.

## An untitled callout
{: .no_toc .text-delta }

```markdown
{: .highlight }
A paragraph
```

{: .highlight }
A paragraph


## A single paragraph callout
{: .no_toc .text-delta }

```markdown
{: .note }
A paragraph
```

{: .note }
A paragraph

```markdown
{: .note-title }
> My note title
>
> A paragraph with a custom title callout
```

{: .note-title }
> My note title
>
> A paragraph with a custom title callout

## A multi-paragraph callout
{: .no_toc .text-delta }

```markdown
{: .important }
> A paragraph
>
> Another paragraph
>
> The last paragraph
```

{: .important }
> A paragraph
>
> Another paragraph
>
> The last paragraph

```markdown
{: .important-title }
> My important title
>
> A paragraph
>
> Another paragraph
>
> The last paragraph
```

{: .important-title }
> My important title
>
> A paragraph
>
> Another paragraph
>
> The last paragraph

## An indented callout
{: .no_toc .text-delta }

```markdown
> {: .highlight }
  A paragraph
```

> {: .highlight }
  A paragraph

## Indented multi-paragraph callouts
{: .no_toc .text-delta }

```markdown
> {: .new }
> > A paragraph
> >
> > Another paragraph
> >
> > The last paragraph
```

> {: .new }
> > A paragraph
> >
> > Another paragraph
> >
> > The last paragraph


## Nested callouts
{: .no_toc .text-delta }

```markdown
{: .important }
> {: .warning }
> A paragraph
```

{: .important }
> {: .warning }
> A paragraph

## Opaque background
{: .no_toc .text-delta }

```markdown
{: .important }
> {: .opaque }
> <div markdown="block">
> {: .warning }
> A paragraph
> </div>
```

{: .important }
> {: .opaque }
> <div markdown="block">
> {: .warning }
> A paragraph
> </div>
