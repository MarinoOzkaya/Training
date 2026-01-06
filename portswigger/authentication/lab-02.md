# Lab:  Username enumeration via response timing

**Category:** Auth 
**Date:** 2026-01-05
**Difficulty:** Medium

## Goal
Enumerate a valid username, brute-force this user's password, then access their account page.

## Vulnerability Summary
Root cause in 1–2 sentences.

## Exploitation Steps (High level)
1. First check for the response with a known invalid username 
2. Check in repeater the response time on a valid vs invalid username
3. (If needed) Use "X-Forwarded-For:1" header to reset timeout
4. Use valid username with longer password and check response time
5. Check invalid username response time with same password
6. Run the valid username and X-Forward-For: in intruder with pitchfork to check response times
7. Find if there is a valid username in the result by looking at response times. Long response time likely means valid username

## Evidence
- 

## Fix / Mitigation
- 

## Notes
- 