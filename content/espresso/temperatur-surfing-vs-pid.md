---
title: "Temperatur-Surfing vs. PID: Was bringt's wirklich?"
description: "PID hält die Temperatur auf 1 °C konstant, Temperatur-Surfing macht das manuell. Was du wann brauchst – und wann es egal ist."
date: 2026-03-15
categories: ["Espresso"]
tags: ["temperatur", "pid", "fortgeschritten", "konsistenz"]
difficulty: "Fortgeschritten"
---

Die Brühtemperatur entscheidet mit über Säure, Süße und Bitterkeit. Aber: Nicht jede Maschine kann die Temperatur exakt halten. Es gibt zwei Wege – **PID** und **Temperatur-Surfing**.

## Das Problem

Klassische Zweikreiser (HX) haben einen Boiler für Brüh- und Dampfwasser. Direkt nach dem Aufheizen ist das Wasser oft viel zu heiß (>100 °C im Brühkopf). Ohne Eingriff schmeckt der erste Shot verbrannt.

## Lösung 1: PID

**PID = Proportional-Integral-Derivative-Regelung**. Ein elektronischer Regelkreis hält die Temperatur konstant – meist auf ±1 °C.

- **Pro:** zuverlässig, einstellbar, kein Eingriff nötig
- **Contra:** Aufpreis, oft nur in besseren Maschinen

## Lösung 2: Temperatur-Surfing

Manueller Workaround bei Maschinen ohne PID:

<div class="step">
  <span class="step-num">1</span>
  <span class="step-title">Cooling Flush</span>
  <div class="step-body">Vor dem Bezug 3–8 Sek. Wasser durchlaufen lassen, um die zu heißen ersten Wasser aus dem Brühkopf zu spülen.</div>
</div>

<div class="step">
  <span class="step-num">2</span>
  <span class="step-title">Wartezeit</span>
  <div class="step-body">5–15 Sekunden warten, bis frisches Wasser aus dem Boiler in den Brühkopf nachzieht.</div>
</div>

<div class="step">
  <span class="step-num">3</span>
  <span class="step-title">Bezug starten</span>
  <div class="step-body">Genau in diesem Fenster ist die Temperatur richtig.</div>
</div>

## Vergleich

| Kriterium | PID | Temperatur-Surfing |
|---|---|---|
| Konstanz | sehr hoch | mittel |
| Aufwand | null | manuell |
| Reproduzierbarkeit | sehr hoch | erfordert Übung |
| Kosten | Maschinen-Aufpreis | null |
| Helle Bohnen | ideal | schwierig |

## Wann PID Pflicht ist

- **Helle Specialty-Röstungen** (1 °C Unterschied schmeckt)
- **Mehrere Shots hintereinander** ohne Wartezeit
- **Reproduzierbarkeit als Lernziel**

## Wann Surfing reicht

- **Klassische dunkle Röstungen** (verzeihen mehr)
- **1–2 Shots am Tag** mit fester Routine
- **HX-Maschinen ab Sweet Spot** mit thermisch stabiler E61-Brühgruppe

<div class="tip">
  <div class="tip-label">Realismus</div>
  Eine PID-fähige Maschine ist die sinnvollste Einzelinvestition, wenn du helle Bohnen ernst nimmst. Ohne PID ist hellere Specialty meist Frust.
</div>

## Häufige Fragen

**Frage: Kann ich PID nachrüsten?**
Bei einigen Maschinen ja — für die Rancilio Silvia gibt es z. B. PID-Kits zum Selbsteinbau (~100–150 €). Bei E61-Maschinen ist ein Nachrüst-PID ebenfalls möglich. Ein Blick ins Kaffee-Netz zeigt, ob es für dein Modell Anleitungen gibt.

**Frage: Welche Temperatur soll ich einstellen?**
92–94 °C ist ein guter Ausgangspunkt. Dunkle Röstungen eher niedriger (90–92 °C), helle eher höher (93–96 °C). Geschmack entscheidet: [sauer](/fehleranalyse/espresso-schmeckt-sauer/) = wärmer, [bitter](/fehleranalyse/espresso-schmeckt-bitter/) = kühler.

**Frage: Macht Temperatur-Surfing meinen Espresso wirklich schlechter?**
Nicht zwingend. Mit Routine und dunklen Bohnen liefert Surfing gute Ergebnisse. Die Inkonsistenz wird erst zum Problem, wenn du helle Bohnen brühst oder reproduzierbare Ergebnisse zum Lernen brauchst. Mehr zur Maschinenwahl im [Ratgeber](/equipment/espressomaschine-kaufen-ratgeber/).
