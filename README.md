# Signup Form

## Overview

This is a "Sign Up" form prototype using React demonstrating the following:

1. Three input fields: username, password, and password confirmation.
1. State persistence.
1. Password and password confirmation match validation.
1. Informing the user when the password and password confirmation do not match.
1. Styling.

## Demo

URL

## Running locally

1. Run `yarn install` or `npm install`.
1. Run `yarn start` or `npm start`.
1. Visit http://localhost:3000 in a browser.

## Running tests

Run `yarn test` or `npm run test`.

## Possible improvements

- Provide a way to access a list of all errors present in the form.
- Allow specification of dependencies for validation functions.
- Break out form hooks into a separate package.
- Add `Checkbox` component.
- Ensure validation for checkbox types are supported.
- Ensure TextField fully supports all possible HTML input types.
- Consider adding more helper methods such as `setFieldValue` from Formik to support a wider range of validation scenarios.
- Investigate how [React Hook Form](https://react-hook-form.com/) and [Formik](https://jaredpalmer.com/formik/) work, and see if anything from those could be incorporated. Namely, analyze their uses of `ref`.
- Consider the possibility of making `TextField` an uncontrolled component to reduce re-renders during validation (as React Hook Form does).
- Set form as `dirty` only when comparison of initial field values to current field values yields a difference.
