# React Router v6 Catch-all Route Issue

This repository demonstrates a common issue encountered when using the catch-all route ('*') in React Router v6.  The catch-all route is intended to handle any routes not explicitly defined, but it may not work correctly if placed incorrectly within the Routes component.

## Problem

The provided `App.js` file shows an example where the catch-all route (`<Route path="*" element={<NotFound />} />`) does not function as expected.  Navigating to a non-existent path does not render the NotFound component.

## Solution

The `AppSolution.js` file demonstrates how to correctly place the catch-all route in the Routes component, ensuring that it captures any undefined routes.