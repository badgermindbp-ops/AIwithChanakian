<p align="center"><img src="logo-mark-round.svg" alt="AI with Chanakian logo" width="120"></p>

# AI with Chanakian

Live at **[aiwithchanakian.com](https://aiwithchanakian.com)**

Landing page for **AI with Chanakian**: personal AI guidance for non-tech people.

- **AI as your Coworker**: for employees and teams (HR, sales, marketing, admin)
- **AI as your Co-Founder**: for small business owners (clinics, salons, shops)

A single static page: plain HTML, CSS and a few lines of JavaScript. No build step, no frameworks.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole page: hero, how it works, paths, offers, about, "in the room" collage, call to action |
| `styles.css` | Animations and layout helpers |
| `assets/chanakian.png` | Hero portrait (background removed) |
| `assets/room-1.jpg` … `room-8.jpg` | Event and speaking photos for the collage (brand logos removed) |

## Before going live

1. **WhatsApp**: every button opens a chat with +91 80563 27917 and a pre-typed message. To change the number, replace `918056327917` in `index.html`.
2. **Booking**: "Book a call" buttons open https://calendly.com/chanakian-p/30min (header, hero and final section).
3. **Lead forms**: "Start as a Coworker" and "Start as a Co-Founder" open pop-up forms. Submissions are emailed to chanakian.p@gmail.com through the free FormSubmit service (formsubmit.co).
   - **First time only:** after the site is live, submit one test entry. FormSubmit sends an activation email to chanakian.p@gmail.com; click **Activate Form**. Until you do, no submissions are delivered.
   - Optional: the activation email also gives you a random alias. Replace `chanakian.p@gmail.com` in the `ENDPOINT` line of `index.html` with it to hide your address from the page source.
4. **Domain**: the footer mentions `aiwithchanakian.com`; update it if you use a different domain.

## Publish with GitHub Pages (free)

1. In this repository, go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. After a minute the site is live at `https://<your-username>.github.io/AIwithChanakian/`.
4. To use your own domain, add it under **Custom domain** on the same page and point your domain's DNS to GitHub Pages.

## Preview locally

Open `index.html` in any browser. That's it.
