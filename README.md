# VectorVersionRepro

in "netcoreapp1.0" everything Just Works (tm)


with "net461" and imagesharp verion "1.0.0-alpha1-00054" also works


now....

if you switch to the new "1.0.0-alpha2-00017"

and DELETE bin&obj and the project.lock.json (doing a clean will NOT help)


let visual studio restore the packages and then press F5

and wait for it to crash
