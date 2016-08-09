Mono.Net.HttpOnlyListener
==================

A fully managed HttpListener implementation extracted from Mono

It's not as complete or capable as the .net implementation of System.Net.HttpListener relying on IIS, but it doesn't require Administrator rights to listen on all interfaces, making it perfect to serve http content for testing.

This fork removes the Mono.Security.dll dependency but as a result also breaks SSL/Crypto compatibility.
