# React Router Dom v6 Catch-all Route Conflict

This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router Dom v6. The problem arises when the catch-all route conflicts with other defined routes, leading to unexpected routing behavior.  The provided solution explains how to correctly implement catch-all routes to avoid such conflicts.

## Problem

The problem arises when a catch-all route is placed in a way that it intercepts routes that should be handled by more specific routes. This causes the catch-all route to be activated instead of the correct route.

## Solution

The solution involves strategically placing the catch-all route at the end of the route definitions, ensuring it only matches URLs not covered by other routes. 