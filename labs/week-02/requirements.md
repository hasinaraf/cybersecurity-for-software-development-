# Week 2 security requirements

Your name: Hasin Araf
Date: 01 OCt 2026

Fill this in as you work, rather than at the end. Where you are unsure, write
that you are unsure and say why. A sentence you can support is worth more than a
confident one you cannot.

---

## 1. What this application is



Atrium is a small internal staff workspace that runs on a user's own computer.
Signed-in staff members can use it to look up colleagues in a staff directory,
read shared resources, and view their profile. The application also supports an
administrator account alongside ordinary staff accounts. The accounts are test
accounts rather than real people, and the application is intended for use in
class.

**Where the assistant's explanation did not match the application.** Anything you
checked and found different, however small. Write "nothing found" if that is the
honest answer.

nothing found

## 2. What is worth protecting

Four assets. For each one, say what it is and what it would cost if it were seen,
changed or unavailable. Write the cost so that somebody outside the team could
understand it.

| Asset | What it costs if this goes wrong |
|---|---|
|  |  |
|  |  |
|  |  |
|  |  |

## 3. The requirements

Three sentences, in your own words. Each one should say what is not allowed and to
whom.

1. Unauthenticated visitors must not be able to read the staff directory; only signed-in Atrium users may view it.
2. The directory must not reveal passwords, password hashes, session credentials, or other authentication secrets to any signed-in user.
3. A staff member's search input must not be able to change the database query or expose records outside the directory's intended staff results.

**Which of these did you write yourself, and which started as a draft from your
assistant?** Say plainly. Both are fine.

## 4. One I rejected or rewrote

- The original sentence:
- My version:
- Which test it failed, and why: (specific / somebody could check it / about this application)

## 5. How somebody would check one of these

Pick one requirement. Write the steps for a person who has never seen Atrium and
cannot ask you anything.

- The requirement:
- Sign in as:
- Steps:
- What result would mean the requirement is met:
- What result would mean it is not met:

---

## Optional, if you had time

Your four requirements in order, most important first, with one sentence each on
why it is in that position.
