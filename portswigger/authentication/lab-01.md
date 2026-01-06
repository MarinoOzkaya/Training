# Lab: Lab: Username enumeration via subtly different responses

**Category:** Auth
**Date:** 2026-01-05
**Difficulty:** Easy

## Goal
Enumerate a valid username, brute-force this user's password, then access their account page.

## Vulnerability Summary
Predictable username and password used which can be enumerated due to site's design on feedback

## Exploitation Steps (High level)
1. Access login page
2. Send login page to Intruder
3. Run intruder for usernames and look for status codes and response times
4. None found - need to focus on the return message 
5. There is a single return with a missing "." in the result. This must be the username
6. Run intruder on passwords with this username
7. Look for different status code (302 found)
8. Enter credentials in portal and they work

## Evidence
Username was afiliados
Password was andrew

## Fix / Mitigation
Fix the typo in the display message

## Notes
