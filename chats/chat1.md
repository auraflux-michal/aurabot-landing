# Aurabot Real Estate Landing

_Started 2026-05-16 19:19 UTC_

---

## User

Create a high-end, professional landing page for "Aurabot" - an AI Voice Assistant specifically designed for Real Estate Agents. 

Design Inspiration:
- Use a structure similar to voize.ai (mobile-first, clean, focused on voice-to-structured-data).
- Aesthetics: Modern Luxury Real Estate. Dark theme with a Deep Charcoal (#1A1A1B) background, White text, and Honey Gold (#D4AF37) accents for CTAs. 
- Layout: Clean, minimalist, using sophisticated sans-serif fonts (like Inter or Montserrat).

Inspiration
https://www.voize.ai/us

Page Structure:
1. Hero Section: 
   - Headline: "Arek: Twój Głosowy Asystent AI, który Sprzedaje, gdy Ty Jesteś w Terenie."
   - Subheadline: "Zautomatyzuj raporty po wizytach, follow-upy na WhatsApp i wpisy do CRM za pomocą głosu. Oszczędź do 1 godziny dziennie."
   - CTA Button: "Zacznij darmowy test" (Gold background).
   - Visual: High-quality mockup of a real estate agent talking into a smartphone.

2. Feature Grid (Voize.ai Style):
   - Module 1: "Raportowanie Głosowe" - Convert speech to CRM data instantly after viewing.
   - Module 2: "Instant Follow-up" - Automatically send WhatsApp/SMS via n8n integration right after the call/visit.
   - Module 3: "Inteligentny Kalendarz" - Voice-command scheduling that syncs with Google Calendar.
   - Module 4: "N8N Integration" - Connect Arek to your existing tools (Aurasoft, CRM, Gmail).

3. "How it Works" Section:
   - Step 1: Pokaż nieruchomość.
   - Step 2: Podyktuj Arkowi kluczowe wnioski i ustalenia.
   - Step 3: Arek aktualizuje CRM, wysyła ofertę klientowi i ustawia przypomnienie o kontakcie.

4. Integration Section:
   - Logos of: n8n, WhatsApp, Google Calendar, Pipedrive, and Slack. 
   - Headline: "Arek współpracuje z Twoimi narzędziami."

5. Trust Section:
   - "Bezpieczeństwo danych: Szyfrowanie klasy bankowej i pełna zgodność z RODO."

6. Footer:
   - Clean, professional with links and a small "Powered by AuraBot" credit.

Animations:
- Subtle fade-ins as you scroll.
- Professional hover effects on buttons.

## Assistant

_[tool: update_todos]_

I'll create an original luxury dark landing page for Aurabot. Setting the aesthetic system first:

**System:** Deep charcoal `#0E0E0F` base with layered `#1A1A1B`, off-white `#F5F1E8` text, honey gold `#D4AF37` accents. Typography pairs Fraunces/serif display with Inter sans for body. Subtle grain texture, hairline gold dividers, scroll-triggered fades.

_[tool: write_file]_

_[tool: done]_

_[tool: fork_verifier_agent]_

Landing page is ready — **Aurabot Landing.html**.

**Design system:**
- Charcoal `#0E0E0F` base with layered surfaces, honey gold `#D4AF37` accents, off-white `#F5F1E8` text
- Fraunces (serif display, italic for gold emphasis) + Inter (body) + JetBrains Mono (labels/meta)
- Subtle film grain overlay, radial gold glows, hairline `rgba(255,255,255,.08)` dividers

**Sections built:**
1. **Hero** — Polish headline with italic-gold accent, animated phone mockup with live transcription card, pulsing gold mic, 3 floating notification cards (CRM updated / WhatsApp sent / Reminder)
2. **Trust marquee** — Cities of polish agencies
3. **Feature grid (4)** — Each module has a unique micro-visual (voice→CRM pill flow, chat bubbles, calendar grid, n8n node graph)
4. **How it works** — 3 oversized italic-gold step numerals
5. **Integrations** — 5-up grid with hand-drawn SVG marks for n8n, WhatsApp, Calendar, Pipedrive, Slack
6. **Trust/Security** — Split card with AES-256, RODO, no-training commitments
7. **CTA banner + Footer** — "Powered by AuraBot" credit included

**Motion:** IntersectionObserver fade-ups with staggered delays, pulsing mic rings, audio waveform, floating cards, subtle button lift + gold glow on hover.

Next steps if you want them: swap the phone-screen content for a real product screenshot, add a testimonial section with agent photos, or branch a light-mode variant via Tweaks.

## User

na wersje pilotaż agent będzie odbierał rozmowę podawał wolne terminy na oglądanie, umawiał wizytę, dodawał do kalendarza i wysłał sms/mail do agenta. Klient będzie też mógł zostawić wiadomość żeby agent oddzwonił wtedy wyślę sms z namiarami na Klienta. Pilotaż będzie płatny 1000 zł + koniguracja. Odzyskujemy czas agenta. CTA TYPU umów się na demo. niech to będzie tylko landingpage na start. uwzględinj zmiany.

## Assistant

_[tool: update_todos]_

_[tool: write_file]_

_[tool: done]_

_[tool: fork_verifier_agent]_

Gotowe — strona przeprojektowana pod **pilotaż**.

**Co się zmieniło:**

- **Hero** — nowy headline: *„Arek odbiera telefon, gdy Ty jesteś w terenie."* Subline opisuje pełny scenariusz: odbiera → proponuje terminy → umawia → SMS. Phone mockup pokazuje teraz **rozmowę na żywo** z klientem i wybór slotu (Pt 16:00 / Sob 11:00 / Pn 18:00). Floating cards: "Odebrane przez Arka", "Wizyta umówiona", "SMS do Ciebie".
- **Pasek statystyk** — 100% odebranych / 24/7 / ~2 min umówienia / 0 utraconych leadów.
- **How it works** — 4 kroki zamiast 3: (01) klient dzwoni → (02) Arek proponuje terminy → (03) wpisuje do kalendarza → (04) wysyła SMS/mail. Pod spodem **ścieżka alternatywna „proszę oddzwonić"** wydzielona jako osobny moduł — Arek przekazuje kontakt SMS-em.
- **Funkcje (4)** — Inbound · Slots · Calendar · Notify. Każda z własnym mikro-wizualem (incoming call ring, slot picker, mini calendar, SMS preview).
- **Pilotaż / Pricing** — nowa sekcja z kartą cenową **1 000 PLN jednorazowo + konfiguracja w cenie**. Lista co wchodzi w skład: konfiguracja, numer z przekierowaniem, integracja z Google Calendar, scenariusz „oddzwoń", wsparcie 1:1.
- **CTA** — wszystkie przyciski na **„Umów się na demo"** (zarówno w nav, hero, pricing, jak i bannerze końcowym).
- **Bezpieczeństwo** — zostało (AES-256, RODO, no-training).
- **Footer** — uproszczony do dwóch kolumn (Produkt, Kontakt) plus brand.

Daj znać, czy chcesz dodać sekcję z FAQ (np. „co się dzieje gdy Arek nie zrozumie klienta", „jaki numer dostaję"), albo prawdziwy formularz demo zamiast linku na `#cta`.

## User

Zrób drugą wersję jasne kolory, w hero zamiast telefonu zdjęcie Potencjalnego Klienta który dzwoni, a obok lewitujące sztabki które już zrobiłeś. Zamiast Arek wszędzie wpisz Agent.

Konfiuracja jednoraznowo będzie płatna, 3000 zł.

Usuń kropkę obok logo i zrób napis aurabot fontem bez szeryfowym. 

Na całej stronie użyj dla nagłówków i tekstów fonta Manrope.

## Assistant

_[tool: copy_starter_component]_

_[tool: write_file]_

_[tool: done]_

_[tool: fork_verifier_agent]_

Gotowe — **Aurabot Landing Light.html** (oryginalna ciemna wersja zostaje obok).

**Co zmienione:**

- **Jasna paleta** — kremowe tło `#FAF7F2`, białe karty `#FFFFFF`, charcoal tekst `#1A1A1B`, gold akcent przyciemniony do `#B8941F` (lepszy kontrast na jasnym).
- **Logo** — sama litera, bez kropki, **„aura*bot*"** w Manrope 700, "bot" w gold.
- **Manrope wszędzie** — usunięty Fraunces; wszystkie nagłówki i body w Manrope (300–800), `letter-spacing: -.035em` na dużych nagłówkach żeby zrobić luksusowe, sklejone proporcje.
- **„Arek" → „Agent"** w całym tekście (hero, how it works, features, pricing, trust, CTA).
- **Hero photo zamiast telefonu** — wstawiony `<image-slot>` w pionowej ramce 380×520, z tagiem „Połączenie · 01:24" i pulsującą zieloną kropką. **Przeciągnij własne zdjęcie klienta na to miejsce** — zapisuje się i zostaje po reloadzie. Domyślnie pokazuje słuchawkę + podpis „Wrzuć tu zdjęcie".
- **Floating cards (sztabki)** — te same 3 lewitujące karty wokół zdjęcia: „Odebrane przez Agenta", „Wizyta umówiona Sob 11:00", „SMS do Ciebie".
- **Pricing 3 000 zł** — opłata jednorazowa, "Konfiguracja — opłata jednorazowa · netto". Hero meta i CTA też zaktualizowane.
- **Przyciski** — primary jest teraz w kolorze gold (na jasnym tle wygląda lepiej niż ciemny przycisk).

## User

Przenieś 0 utraconych leadów jako 3 pozycja.

## Assistant

_[tool: grep]_

_[tool: str_replace_edit]_

Zamienione — "0 utraconych leadów" jest teraz na trzeciej pozycji, a "~ 2 min średni czas umówienia" na czwartej.

## User

Zmiany
- font "JetBrains Mono zmień na manrope
- ze zdjęcia usuń "połączenie i dodaj je np. od lewitującego modułu "odebrane przez Agenta
- ikony zrób proste bez kwadratu pod nimi.
- usuń z tła w hero kratkę
- zmień kolory na bardziej premium, pod agencje nieruchomości może główny kolor primiary 
Tło Główne: Warm Alabaster (#FBFBFA)
Co to jest: Ciepła, luksusowa biel (odcień alabastru lub czystego jedwabiu).

Rola w designie: Stanowi 60% strony. To nie jest "szpitalna", rażąca biel – ma w sobie minimalną domieszkę ciepła.

Efekt premium: Nadaje stronie lekkość nowoczesnej galerii sztuki. Sprawia, że cała witryna "oddycha" i wygląda niezwykle prestiżowo.

2. Tekst i Nagłówki: Deep Obsidian (#111111)
Co to jest: Głęboka, matowa czerń wulkaniczna.

Rola w designie: Stanowi około 30% strony. Używana do wszystkich głównych napisów, tytułów oraz najważniejszych ikon.

Efekt premium: Zapewnia ostry jak brzytwa kontrast na jasnym tle. Nadaje tekstom "magazynowy" charakter – jak w ekskluzywnych albumach o architekturze wnętrz.

3. Akcent Główny (CTA): Deep Burgundy (#841839)
Co to jest: Głęboki, szlachetny burgund (odcień dojrzałego wina / marsali). Twój strzał w dziesiątkę.

Rola w designie: Dokładnie 10% strony. Używany wyłącznie do przycisków akcji (np. „Zacznij Test”), hoverów oraz kluczowych elementów interfejsu (jak strzałki czy mikrofony).

Efekt premium: W nieruchomościach burgund to synonim najwyższej półki (Ultra-Luxury, stare kamienice, prestiżowe fundusze). Na jasnym tle wygląda niesamowicie magnetycznie – natychmiast ściąga wzrok klienta na przycisk rejestracji.

## Assistant

_[tool: read_file]_

_[tool: str_replace_edit]_

_[tool: done]_

_[tool: fork_verifier_agent]_

Wszystko zaktualizowane:

- **Paleta premium** — `#FBFBFA` alabaster, `#111111` obsidian, `#841839` burgundy. Burgund zastępuje gold w przyciskach, mikrofonach, akcentach, slotach, podkreśleniach.
- **Manrope wszędzie** — JetBrains Mono usunięty z importu i z `--mono` (zmienna teraz też wskazuje na Manrope, więc labelki/mono zachowują ten sam tracking-uppercase look, ale w spójnym foncie).
- **Ikony bez kwadratów** — `.float-card .ic` straciło tło, padding i wielkość; teraz to czysty 22px ikona w kolorze burgundy.
- **Tag „Połączenie · 01:24" przeniesiony** — pulsująca pigułka z ramki zdjęcia zniknęła; floating card „Odebrane przez Agenta" dostała w eyebrowie „· 01:24".
- **Kratka w hero usunięta** — został tylko miękki burgundowy radial glow w tle.

