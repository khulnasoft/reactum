<h1 align="center" style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-weight: 900; font-size: 3rem;">⚛️ Reactum</h1>

<p align="center">
  <a href="https://app.fossa.com/projects/git%2Bgithub.com%2Fkhulnasoft%2Freactum?ref=badge_shield&issueType=license">
    <img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkhulnasoft%2Freactum.svg?type=shield&issueType=license" alt="FOSSA Status" />
  </a>
</p>

<p align="center">
  A modern, server-safe collection of essential & experimental React hooks – built with ❤️ by the <a href="https://khulnasoft.com">Khulnasoft</a> team.
</p>

<p align="center">
  <strong>Compatible with React 18+</strong>
</p>

---

## 📦 Installation

### Standard

```bash
npm i reactum
```

### Experimental

```bash
npm i reactum@experimental react@experimental react-dom@experimental
```

---

## 🧰 Standard Hooks

A curated set of utility hooks, optimized for modern React apps:

| Hook | Description |
|------|-------------|
| [`useBattery`](https://hooks.khulnasoft.com/usebattery) | Monitor battery status |
| [`useClickAway`](https://hooks.khulnasoft.com/useclickaway) | Trigger when clicking outside an element |
| [`useCopyToClipboard`](https://hooks.khulnasoft.com/usecopytoclipboard) | Copy content to clipboard |
| [`useCounter`](https://hooks.khulnasoft.com/usecounter) | Simple counter logic |
| [`useDebounce`](https://hooks.khulnasoft.com/usedebounce) | Debounce any fast-changing value |
| [`useDefault`](https://hooks.khulnasoft.com/usedefault) | Revert to default when input is invalid |
| [`useDocumentTitle`](https://hooks.khulnasoft.com/usedocumenttitle) | Set document title dynamically |
| [`useFavicon`](https://hooks.khulnasoft.com/usefavicon) | Change tab icon programmatically |
| [`useGeolocation`](https://hooks.khulnasoft.com/usegeolocation) | Access user geolocation |
| [`useHistoryState`](https://hooks.khulnasoft.com/usehistorystate) | Sync state with browser history |
| [`useHover`](https://hooks.khulnasoft.com/usehover) | Detect hover state |
| [`useIdle`](https://hooks.khulnasoft.com/useidle) | Detect user inactivity |
| [`useIntersectionObserver`](https://hooks.khulnasoft.com/useintersectionobserver) | Track element visibility |
| [`useIsClient`](https://hooks.khulnasoft.com/useisclient) | Check if rendering on client |
| [`useIsFirstRender`](https://hooks.khulnasoft.com/useisfirstrender) | Run logic only on first render |
| [`useList`](https://hooks.khulnasoft.com/uselist) | Manage arrays in state |
| [`useLocalStorage`](https://hooks.khulnasoft.com/uselocalstorage) | Persist state in localStorage |
| [`useLockBodyScroll`](https://hooks.khulnasoft.com/uselockbodyscroll) | Prevent page scroll |
| [`useLongPress`](https://hooks.khulnasoft.com/uselongpress) | Handle long-press events |
| [`useMap`](https://hooks.khulnasoft.com/usemap) | Map-like state management |
| [`useMeasure`](https://hooks.khulnasoft.com/usemeasure) | Measure DOM elements |
| [`useMediaQuery`](https://hooks.khulnasoft.com/usemediaquery) | Respond to CSS media queries |
| [`useMouse`](https://hooks.khulnasoft.com/usemouse) | Track mouse position |
| [`useNetworkState`](https://hooks.khulnasoft.com/usenetworkstate) | Monitor online/offline status |
| [`useObjectState`](https://hooks.khulnasoft.com/useobjectstate) | Mergeable object state hook |
| [`useOrientation`](https://hooks.khulnasoft.com/useorientation) | Track screen orientation |
| [`usePreferredLanguage`](https://hooks.khulnasoft.com/usepreferredlanguage) | Detect user's language preference |
| [`usePrevious`](https://hooks.khulnasoft.com/useprevious) | Access previous value |
| [`useQueue`](https://hooks.khulnasoft.com/usequeue) | FIFO queue state |
| [`useRenderCount`](https://hooks.khulnasoft.com/userendercount) | Count component renders |
| [`useRenderInfo`](https://hooks.khulnasoft.com/userenderinfo) | Detailed render tracking |
| [`useScript`](https://hooks.khulnasoft.com/usescript) | Dynamically load scripts |
| [`useSessionStorage`](https://hooks.khulnasoft.com/usesessionstorage) | Persist state in sessionStorage |
| [`useSet`](https://hooks.khulnasoft.com/useset) | Set-based state |
| [`useThrottle`](https://hooks.khulnasoft.com/usethrottle) | Throttle changing values |
| [`useToggle`](https://hooks.khulnasoft.com/usetoggle) | Simple boolean toggle |
| [`useVisibilityChange`](https://hooks.khulnasoft.com/usevisibilitychange) | Detect tab visibility changes |
| [`useWindowScroll`](https://hooks.khulnasoft.com/usewindowscroll) | Track scroll position |
| [`useWindowSize`](https://hooks.khulnasoft.com/usewindowsize) | Track window size |

---

## 🧪 Experimental Hooks

Bleeding-edge features under active development:

| Hook | Description |
|------|-------------|
| [`useContinuousRetry`](https://hooks.khulnasoft.com/usecontinuousretry) | Retry logic with exponential backoff |
| [`useCountdown`](https://hooks.khulnasoft.com/usecountdown) | Countdown timer |
| [`useEventListener`](https://hooks.khulnasoft.com/useeventlistener) | Add/remove DOM event listeners |
| [`useFetch`](https://hooks.khulnasoft.com/usefetch) | Lightweight data fetching |
| [`useInterval`](https://hooks.khulnasoft.com/useinterval) | Run interval-based logic |
| [`useIntervalWhen`](https://hooks.khulnasoft.com/useintervalwhen) | Conditional interval execution |
| [`useKeyPress`](https://hooks.khulnasoft.com/usekeypress) | Keyboard key tracking |
| [`useLogger`](https://hooks.khulnasoft.com/uselogger) | Lifecycle logging for components |
| [`usePageLeave`](https://hooks.khulnasoft.com/usepageleave) | Detect mouse leaving the page |
| [`useRandomInterval`](https://hooks.khulnasoft.com/userandominterval) | Randomized interval execution |
| [`useTimeout`](https://hooks.khulnasoft.com/usetimeout) | Delay logic using timeout |

---

## 📚 Documentation

Full documentation with examples and demos available at:

👉 **[hooks.khulnasoft.com](https://hooks.khulnasoft.com)**

---

## 🤝 Contributing

Found a bug? Want a new hook? Fork, commit, and send a PR!  
We welcome all contributions – big or small.

```bash
git clone https://github.com/khulnasoft/reactum.git
cd reactum
npm install
npm run dev
```

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).  
License scanning provided by [FOSSA](https://fossa.com).

---

<p align="center">
  Built with 🛠️ by <a href="https://khulnasoft.com">Khulnasoft</a> • Star us on <a href="https://github.com/khulnasoft/reactum">GitHub ⭐</a>
</p>
