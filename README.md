# Simple GUI for Login in WPF

My first project. One factor auth.

>Status: released ✅<br>
>Version: not applicable<br>
>Date released: 12/16/2025

## What does it do? - Purpose
Opens a window as a gatekeeper what only allows access when both username and password are correct.

## Content
Single form without dependencies.
Two textbox, one button.

## How does it work? - Behavior
The button "Connect/ Enter" is configured to negate access when:
* Both username and password are `null` or empty;
* Username or password is `null` or empty;
* Both are incorrect;
* Username or password is incorrect.

When is allowed to access:
* `MessageBox.Show("Success");`

## What was used? - Resources
GUI          | .NET  | SQL | Web
------------ | ----- | --- | ---
WPF          | v.8.0 | No  | No
