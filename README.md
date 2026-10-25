# GuestPilot

**A Claude-powered co-host for solo rental hosts.**

GuestPilot is a free, open-source autopilot for guest messaging. It sends the messages every stay needs, answers guest questions from your own property guide, and asks you when it is not sure. You stay in control; GuestPilot does the typing.

Built at the Claude Impact Lab Hackathon (Seattle AI Week, Oct 25, 2026).

## The problem

Solo hosts spend hours every week on the same messages: the welcome note with the door code, the check-in instructions, the checkout reminder, the review request, and the same guest questions again and again (WiFi, parking, early check-in, the hot tub). It is repetitive, easy to forget, and one missed message can cost a five-star review.

Existing tools do not solve this for a one-property host. Platform inboxes only suggest replies for you to send yourself. Full property management systems bundle messaging into subscriptions built and priced for large operators, and even their top tiers will not auto-answer whole categories of questions.

## What GuestPilot does

- **Scheduled messages that send themselves.** Booking confirmed, day before arrival, check-in day, checkout: the right message goes out at the right time, filled in with the guest's name, dates, and your property details.
- **Answers guest questions from your property guide.** You write your property's facts once (check-in steps, amenities, house rules, local tips). GuestPilot answers from that guide, in your voice.
- **Escalates instead of guessing.** A question outside the guide goes straight to you with a suggested reply you can approve in one tap. Nothing risky is ever sent on a guess.
- **Shows its work.** Every message sent and question answered appears in one owner inbox, with a full history and one-tap override.

## Setup (about 10 minutes, no coding)

1. **Get a Claude API key** from Anthropic and add it when GuestPilot first runs.
2. **Fill in your property guide.** One plain-text file: address, door code, WiFi, parking, amenities, house rules, and your local recommendations. Write it like you would brief a friend who is covering for you.
3. **Personalize the message templates.** Welcome, check-in, checkout, and review-request templates are plain text with blanks like {guest_name} and {checkin_date}. Edit them in any text editor, or keep the defaults.
4. **Connect your bookings and press start.** GuestPilot watches for new bookings and guest messages and runs your messaging from there.

## Who it is for

- Solo and small short-term rental hosts (1 to 5 properties)
- Anyone who books, confirms, reminds, and answers repeat questions: cleaners, tour operators, salons, clinics. The guide and templates adapt to any booking business.

## Demo

Demo video: coming with the hackathon submission (Oct 25, 2026).

## Status

Hackathon build in progress on Oct 25, 2026. Core scope for the day: the scheduled message engine plus the question-answering agent with escalation, demoed end to end on a simulated stay. Stretch: cleaner turnover coordination with photo verification.

## License

MIT. Use it, fork it, make it yours.
