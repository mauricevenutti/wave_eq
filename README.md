# Wellengleichung

Interaktives Applet zur schwingenden Saite mit festen Enden, $u_{tt} = c^2 u_{xx}$, $u(x,0) = f(x)$, $u_t(x,0) = 0$.

**[Applet öffnen](https://mauricevenutti.github.io/wave_eq/)**

- **Fourier:** Zerlegung von $f$ in Moden $c_k \sin(k\pi x/L)$, Teilsumme $S_n$ mit wählbarem $n$, Zeitverlauf von exakter Lösung und Approximation.
- **Wellenausbreitung:** $u = \tfrac12\left[f^*(x-ct) + f^*(x+ct)\right]$ mit der ungeraden, $2L$-periodischen Fortsetzung $f^*$.
- **Ausschnitt:** umschaltbar zwischen $[-L/2,\,3L/2]$ und $[-L,\,3L]$; im grossen Fenster wird die ungerade, $2L$-periodische Fortsetzung blass mitgezeichnet.
- **Ton:** Dauerton aus den ersten $n$ Koeffizienten $c_k$ (Grundton 440 Hz), mit aufklappbarer Tabelle der Zerlegung.

## Quellen

Instrumente: gemessene Spektren des Tons A4, [SHARC (Sandell)](https://hackage.haskell.org/package/sharc-timbre).
