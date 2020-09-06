.theme-dark {
    --foreground-1: red;
    --foreground-2: red;
    --foreground-divider: #dadada;
    --background-1: red;
    --background-2: red;
    --box-shadow: 0 0 15px 2px rgba(0, 0, 0, 0.2);
    --scrollbar: rgb(53, 55, 63, 0.5);
    --tooltips: #2d323c;
    --pages-box: var(--message-box);
    --pages-box-footer: #191b20;
    --pages-separator: rgba(255, 255, 255, 0.05);
    --user-popout: var(--dropdown);
    --user-popout-body: #1a1c22;
    --user-popout-message: #15171c;
    --settings-box: var(--message-box);
    --settings-box-hover: #16191d;
    --settings-box-footer: #171a1f;
    --settings-input: #131519;
    --settings-paginator: rgba(0, 0, 0, 0.2);
    --settings-separator: rgba(255, 255, 255, 0.05);
    --dropdown: #1e2127;
    --dropdown-header: #252830;
    --dropdown-item-hover: #22262d;
    --message-box: #1b1e23;
    --message-box-divider: #20242a;
    --message-embed: #171a1f;
    --message-button: #2d323c;
    --server-background: #1e2127;
    --server-hovered: #20242a;
    --server-selected: #22262d;
    --server-folders: var(--server-background);
    --search-filter-hover: #22262d;
    --search-result-header: #1e2127;
    --channel-selected-bg: #20242a;
    --channel-hovered-bg: #1c1f25;
    --channel-unread-bg: transparent;
    --channel-selected-text: var(--text-1);
    --channel-unread-text: var(--text-2);
    --channel-muted-text: var(--text-dark);
    --channel-hovered-text: var(--text-1);
    --modal-connection: var(--background-1);
    --modal-list: #15171c;
    --modal-badge-invert: invert(0);
    --modal-bg1-search: var(--search-filter-hover);
    --text-1: #fff;
    --text-2: #c9c9c9;
    --text-3: #999a9b;
    --text-4: #717173;
    --text-dark: #565759;
  }
  .theme-light {
    --foreground-1: #fff;
    --foreground-2: #f6f6f6;
    --foreground-divider: #dadada;
    --background-1: #f2f2f2;
    --background-2: #e8e8e8;
    --box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
    --scrollbar: rgba(12, 12, 12, 0.3);
    --tooltips: #fff;
    --pages-box: var(--message-box);
    --pages-box-footer: #f5f5f5;
    --pages-separator: rgba(0, 0, 0, 0.1);
    --user-popout: var(--dropdown);
    --user-popout-body: #f8f8f8;
    --user-popout-message: #e5e5e5;
    --settings-box: var(--message-box);
    --settings-box-hover: #fafafa;
    --settings-box-footer: #f5f5f5;
    --settings-input: var(--settings-box-footer);
    --settings-paginator: rgba(0, 0, 0, 0.05);
    --settings-separator: #ddd;
    --dropdown: #fff;
    --dropdown-item-hover: #f8f8f8;
    --message-box: #fff;
    --message-box-divider: #ddd;
    --message-embed: #eee;
    --message-button: var(--message-box);
    --server-background: #fff;
    --server-selected: #fff;
    --server-hovered: #fafafa;
    --server-folders: var(--server-background);
    --search-filter-hover: #f5f5f5;
    --search-result-header: #fff;
    --channel-selected-bg: #fff;
    --channel-hovered-bg: #fafafa;
    --channel-unread-bg: transparent;
    --channel-selected-text: var(--text-1);
    --channel-unread-text: var(--text-2);
    --channel-muted-text: var(--text-dark);
    --channel-hovered-text: var(--text-1);
    --modal-connection: #fff;
    --modal-list: #f8f8f8;
    --modal-badge-invert: invert(1);
    --modal-bg1-search: #fff;
    --text-1: #000;
    --text-2: #111;
    --text-3: #222;
    --text-4: #333;
    --text-dark: #666;
  }
  :root {
    --roundness: 50px;
    --message-padding: var(--chat-message-padding, 20px);
    --message-spacing: var(--chat-message-spacing, 20px);
    --bd-blue: rgba(var(--accent), 1);
    --text-link: rgba(var(--accent), 1);
    --dark-modal-background: #171a1f;
    --dark-modal-item: #1c1f25;
    --dark-modal-footer: #131519;
    --light-modal-background: #f8f8f8;
    --light-modal-item: #fff;
    --light-modal-footer: #eee;
    --green: #43b581;
    --greenDark: #359066;
    --yellow: #faa61a;
    --yellowDark: #dc8b05;
    --red: #f04747;
    --redDark: #a83232;
    --purple: #593695;
    --purpleDark: #432870;
    --blurple: #7289da;
    --blurpleDark: #677bc4;
    --nitro: #ff73fa;
    --spotify-green: #1db954;
    --spotify-green-dark: #168d40;
    --twitch-purple: #593695;
    --twitch-purple-dark: #4e2f82;
  }
  ::-webkit-input-placeholder, body, button, input, select, textarea {
    font-family: var(--font, "Roboto"), Whitney;
  }
  #app-mount .tooltipBlack-PPG47z {
    background: var(--tooltips);
    color: var(--text-1);
    text-align: center;
  }
  #app-mount .tooltipBlack-PPG47z .tooltipPointer-3ZfirK {
    border-top-color: var(--tooltips);
  }
  ::selection {
    background: rgba(var(--accent), 1);
    color: #fff;
  }
  .css-181m2lf-menu {
    background: var(--dropdown);
    border: none;
  }
  .themeDefault-24hCdX.valueChecked-m-4IJZ, .ui-switch.checked {
    background-color: rgba(var(--accent), 1) !important;
  }
  #app-mount .attachment-33OFj0,
  #app-mount .wrapper-35wsBm,
  #app-mount code {
    background: var(--message-embed);
    border-color: var(--message-embed);
  }
  .wordmarkWindows-1v0lYD {
    margin-top: 2px;
    padding-left: 6px;
  }
  .wordmarkWindows-1v0lYD svg {
    -webkit-mask: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAi4AAABACAQAAACXIjRXAAAACXBIWXMAAAsTAAALEwEAmpwYAAAFF2lUWHRYTUw6Y29tLmFkb2JlLnhtcAAAAAAAPD94cGFja2V0IGJlZ2luPSLvu78iIGlkPSJXNU0wTXBDZWhpSHpyZVN6TlRjemtjOWQiPz4gPHg6eG1wbWV0YSB4bWxuczp4PSJhZG9iZTpuczptZXRhLyIgeDp4bXB0az0iQWRvYmUgWE1QIENvcmUgNS42LWMxNDIgNzkuMTYwOTI0LCAyMDE3LzA3LzEzLTAxOjA2OjM5ICAgICAgICAiPiA8cmRmOlJERiB4bWxuczpyZGY9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkvMDIvMjItcmRmLXN5bnRheC1ucyMiPiA8cmRmOkRlc2NyaXB0aW9uIHJkZjphYm91dD0iIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtbG5zOmRjPSJodHRwOi8vcHVybC5vcmcvZGMvZWxlbWVudHMvMS4xLyIgeG1sbnM6cGhvdG9zaG9wPSJodHRwOi8vbnMuYWRvYmUuY29tL3Bob3Rvc2hvcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RFdnQ9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZUV2ZW50IyIgeG1wOkNyZWF0b3JUb29sPSJBZG9iZSBQaG90b3Nob3AgQ0MgMjAxOCAoV2luZG93cykiIHhtcDpDcmVhdGVEYXRlPSIyMDE5LTEyLTAzVDAyOjU0OjM4KzExOjAwIiB4bXA6TW9kaWZ5RGF0ZT0iMjAxOS0xMi0wM1QwMjo1ODoxOSsxMTowMCIgeG1wOk1ldGFkYXRhRGF0ZT0iMjAxOS0xMi0wM1QwMjo1ODoxOSsxMTowMCIgZGM6Zm9ybWF0PSJpbWFnZS9wbmciIHBob3Rvc2hvcDpDb2xvck1vZGU9IjEiIHBob3Rvc2hvcDpJQ0NQcm9maWxlPSJEb3QgR2FpbiAyMCUiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6MDQwOTkzM2YtYThhMi1hNTRk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") center/cover no-repeat;
    background: var(--text-1);
    opacity: 0.5;
    height: 10px !important;
    width: 88px !important;
  }
  .wordmarkWindows-1v0lYD svg path {
    display: none;
  }
  #app-mount {
    background: var(--background-2);
  }
  #app-mount .app-2rEoOp, #app-mount .bg-h5JY_x {
    background-color: var(--background-2);
  }
  ::-webkit-scrollbar {
    width: 8px !important;
    height: 8px !important;
  }
  ::-webkit-scrollbar,
  ::-webkit-scrollbar-track,
  ::-webkit-scrollbar-track-piece {
    border-color: transparent !important;
    background: transparent !important;
  }
  ::-webkit-scrollbar-thumb {
    border-radius: 10px !important;
    border: none !important;
    background-clip: content-box !important;
    background-color: var(--scrollbar) !important;
  }
  ::-webkit-scrollbar-corner {
    visibility: hidden !important;
  }
  .scrollerThemed-2oenus.themeHidden-2yP93k .scroller-2FKFPG::-webkit-scrollbar,
  .scrollerThemed-2oenus.themeHidden-2yP93k .scroller-2FKFPG::-webkit-scrollbar-corner,
  .scrollerThemed-2oenus.themeHidden-2yP93k .scroller-2FKFPG::-webkit-scrollbar-thumb,
  .scrollerThemed-2oenus.themeHidden-2yP93k .scroller-2FKFPG::-webkit-scrollbar-track {
    display: none !important;
  }
  #app-mount .title-3qD0b-, #app-mount .container-1r6BKw {
    background: var(--background-1);
  }
  #app-mount .title-3qD0b- .children-19S4PO:after, #app-mount .container-1r6BKw .children-19S4PO:after {
    content: none;
  }
  #app-mount .title-3qD0b- .wrapper-3WhCwL, #app-mount .container-1r6BKw .wrapper-3WhCwL {
    background: rgba(var(--accent), 0.1);
    color: rgba(var(--accent), 1);
  }
  #app-mount .title-3qD0b- .wrapper-3WhCwL:hover, #app-mount .container-1r6BKw .wrapper-3WhCwL:hover {
    color: #fff;
    background: rgba(var(--accent), 1);
  }
  #app-mount .container-3T1zWi:before {
    content: none;
  }
  #app-mount .searchBar-3dMhjb {
    background: var(--background-1);
  }
  #app-mount .topic-TCb_qw a {
    color: rgba(var(--accent), 1);
    text-decoration: underline;
  }
  #app-mount #bd-customcss-attach-controls {
    background: var(--background-2);
    box-shadow: none;
    position: relative;
  }
  #app-mount #bd-customcss-attach-controls .checkbox-group {
    position: absolute;
    bottom: 5px;
    left: 5px;
  }
  #app-mount #bd-customcss-attach-controls .btn.btn-primary {
    background: var(--foreground-2) !important;
    border: none !important;
    margin-top: 0;
    width: 33.33% !important;
  }
  #app-mount #bd-customcss-attach-controls .btn.btn-primary:hover {
    background: var(--foreground-1) !important;
  }
  #app-mount #bd-customcss-attach-controls .help-text {
    text-align: right;
  }
  #app-mount #bd-customcss-attach-controls #bd-customcss-detach-controls-button span {
    display: none;
  }
  #app-mount .ace-monokai {
    background-color: var(--background-2);
  }
  #app-mount .ace-monokai .ace_gutter {
    background: transparent;
  }
  #app-mount.bd-detached-editor .editor-wrapper {
    height: calc(100% + 22px);
  }
  #app-mount.bd-detached-editor #bd-customcss-attach-controls {
    height: 55px;
  }
  #app-mount.bd-detached-editor #bd-customcss-detach-controls-button span[style="font-size: 10px; margin-left: 5px;"] {
    position: absolute;
    bottom: 0;
  }
  .colorMuted-HdFt4q.size12-3cLvbJ:first-child:before {
    content: "MinimalCord v1.0.3 by Gibbu";
    display: block;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] {
    background-color: var(--background-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegionScroller-26nc1e, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .standardSidebarView-3F1I7i {
    background: transparent;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .item-3T2z1R {
    background: var(--background-2);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .item-3T2z1R.passthroughSelected-1Eq0Kl {
    background: rgba(var(--accent), 1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .item-3T2z1R.allowSelected-25S_i5 {
    background: #43b581;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .item-3T2z1R.denySelected-1mh2mZ {
    background: #f04747;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .anchor-3Z-8Bb:not(.embedLink-1G1K1D) {
    color: rgba(var(--accent), 1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .scroller-305q3I {
    background: transparent;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .barFill-23-gu- {
    background: rgba(var(--accent), 1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .lookOutlined-3sRXeN.colorRed-1TFJan {
    background: var(--red);
    color: #fff;
    border-color: var(--red);
    transition: 0.2s ease;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .lookOutlined-3sRXeN.colorRed-1TFJan:hover {
    background: var(--redDark);
    border-color: var(--redDark);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .container-1nZlH6, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .css-15ejc46-control, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .css-1yegjoj-control, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .css-2yldzf-control, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .input-cIJ7To, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .lookFilled-1h1y05.select-1Pkeg4 {
    background: var(--settings-input);
    border: none;
    color: var(--text-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .css-1k00wn6-singleValue {
    color: var(--text-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .css-12qlrak-indicatorContainer {
    opacity: 1;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .checked-3_4uQ9[style*="border-color: rgb(114, 137, 218)"] {
    border-color: rgba(var(--accent), 1) !important;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .checked-3_4uQ9[style*="border-color: rgb(114, 137, 218)"] polyline {
    stroke: rgba(var(--accent), 1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .radioGroup-1GBvlr .item-26Dhrx[style*="background-color: rgb(114, 137, 218)"] {
    background-color: rgba(var(--accent), 1) !important;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .radioGroup-1GBvlr .item-26Dhrx[style*="background-color: rgb(114, 137, 218)"]>label {
    width: 100%;
    display: flex;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .radioGroup-1GBvlr .item-26Dhrx[style*="background-color: rgb(114, 137, 218)"]>label .label-cywgfr {
    flex: 1;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .radioGroup-1GBvlr .cardPrimaryEditable-3KtE4g {
    background: var(--settings-box);
    border: none;
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .cardPrimaryEditable-3KtE4g {
    background: var(--settings-box);
    border: none;
    box-shadow: var(--box-shadow);
    padding: 0;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .cardPrimaryEditable-3KtE4g .divider-3573oO {
    display: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .cardPrimaryEditable-3KtE4g .formActions-34l65m {
    background: var(--settings-box-footer);
    padding: 20px;
    box-sizing: border-box;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .codeRedemptionRedirect-1wVR4b {
    background-color: var(--settings-box);
    box-shadow: var(--box-shadow);
    border: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .container-2VW0UT {
    background: var(--settings-box) !important;
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP {
    background: var(--background-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP .item-PXvHYJ, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP .ui-tab-bar-item {
    color: var(--text-2);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP .item-PXvHYJ:hover, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP .ui-tab-bar-item:hover {
    background: var(--channel-hovered-bg);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP .item-PXvHYJ.selected, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP .item-PXvHYJ.selected-3s45Ha, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP .ui-tab-bar-item.selected, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegionScroller-3MXcoP .ui-tab-bar-item.selected-3s45Ha {
    background: var(--channel-selected-bg);
    color: var(--text-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy {
    background: transparent;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .cardPrimary-1Hv-to {
    border: none;
    background: var(--settings-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .cardPrimary-1Hv-to .h5-18_1nd {
    color: var(--text-3);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .cardPrimary-1Hv-to .viewBody-2Qz-jg {
    color: var(--text-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .userSettingsSecurity-3IYeMF {
    margin-top: 20px;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .userSettingsSecurity-3IYeMF>.children-rWhLdy {
    background: var(--settings-box);
    padding: 15px;
    box-sizing: border-box;
    border-radius: 5px;
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .userSettingsSecurity-3IYeMF>.children-rWhLdy .marginBottom40-2vIwTv.marginTop40-i-78cZ {
    margin: 0;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .userInfoEditing-1CEzdT {
    border: none;
    background: var(--settings-box);
    box-shadow: var(--box-shadow);
    padding: 0;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .userInfoEditing-1CEzdT>div:first-child {
    padding: 20px;
    box-sizing: border-box;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .userInfoEditing-1CEzdT .divider-3573oO {
    display: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .userInfoEditing-1CEzdT>div:last-child {
    padding: 20px;
    box-sizing: border-box;
    background: var(--settings-box-footer);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .authedApp-mj2Hmd {
    background: var(--settings-box);
    border: none;
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connection-1fbD7X {
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connection-1fbD7X .anchor-3Z-8Bb {
    color: #fff;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connection-1fbD7X .connectionHeader-2MDqhu {
    border: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connection-1fbD7X .integration-3kMeY4 {
    border: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connectedAccounts-2-XP1G {
    display: flex;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connectedAccounts-2-XP1G .accountBtn-2Nozo3 {
    margin: 0;
    flex: 1;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connectedAccounts-2-XP1G .accountBtn-2Nozo3:first-child button {
    border-radius: 5px 0 0 5px;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connectedAccounts-2-XP1G .accountBtn-2Nozo3:last-child button {
    border-radius: 0 5px 5px 0;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connectedAccounts-2-XP1G .accountBtn-2Nozo3 button {
    width: 100%;
    border-radius: 0;
    padding: 0;
    background-color: var(--background-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .connectedAccounts-2-XP1G .accountBtn-2Nozo3 button:hover {
    background-color: var(--background-2);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentHistory-2FXzro .verticalFit-waKLYN {
    overflow: visible;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentHistory-2FXzro .verticalFit-waKLYN .scroller-2FKFPG::-webkit-scrollbar {
    display: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A {
    background-color: var(--settings-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A .paymentRow-2e7VM6 {
    border-bottom-color: var(--foreground-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A .paginator-166-09 {
    background: transparent;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A .paginator-166-09 .bottomDivider-1K9Gao {
    border: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A .pageActions-1SVAnA {
    background: var(--settings-box-footer);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A .payment-xT17Mq {
    background: transparent;
    transition: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A .payment-xT17Mq .expandedInfo-3kfShd {
    background: transparent;
    margin-bottom: 0;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A .payment-xT17Mq:hover {
    background: var(--settings-box-hover);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .paymentPane-3bwJ6A .payment-xT17Mq:not(.hoverablePayment-Yc6mK7) {
    background: var(--settings-box-hover);
    box-shadow: inset 4px 0 0 rgba(var(--accent), 1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .card-VoqMMK form>div {
    padding: 0 20px;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .card-VoqMMK form>div:first-child {
    padding-top: 20px;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .card-VoqMMK form>label {
    padding: 0 20px;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .card-VoqMMK form .formActions-34l65m {
    padding: 20px;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .pageButtonNext-V2kUq0, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .pageButtonPrev-1Y-47D, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .pageIndicator-1gAbyA {
    border: none;
    background: var(--settings-paginator);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .detailsBlock-FoDTGA, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .tier1Banner-1B_WXY {
    background-image: none;
    background-color: var(--settings-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .cardWrapper-2Min21 {
    background: var(--settings-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .progress-1IcQ3A {
    background: var(--settings-box);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .notches-1sAcEM {
    background: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .game-1ipmAa {
    box-shadow: 0 1px 0 var(--settings-separator);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .game-1ipmAa .removeGame-2JFGPn {
    background-color: var(--settings-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .game-1ipmAa:before {
    background-color: var(--settings-box);
    box-shadow: var(--box-shadow);
    border: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .searchBox-3Y2Vi7 {
    background: var(--background-2);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .divider-3573oO {
    background-color: var(--settings-separator);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .hiddenLibraryApplication-2esFER {
    border-bottom-color: var(--settings-separator);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .hiddenLibraryApplication-2esFER:before, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .hiddenLibraryApplication-2esFER .restoreButton-22-SIW {
    border: none;
    background: var(--settings-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .item-3eFBNF {
    box-shadow: inset 0 -1px 0 var(--settings-separator);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .auditLog-3jNbM6 {
    border: none;
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .headerClickable-2IVFo9, #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .headerDefault-1wrJcN {
    background: var(--settings-box);
    border: none;
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .headerExpanded-CUEwZ5 {
    background-color: var(--settings-box);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .changeDetails-bk98pu {
    background: var(--background-1);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .card-FDVird .button-2CgfFz {
    background-color: var(--settings-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy .card-FDVird:before {
    background-color: var(--settings-box);
    box-shadow: var(--box-shadow);
    border: none;
  }
  .theme-light #user-settings>div:nth-child(3)>div>div:nth-child(2)>div>div>div>main>div>div>div:nth-child(2)>div>div:nth-child(2)>label>div.label-cywgfr.labelClickable-11AuB8.labelForward-1wfipV>div:after {
    content: "Work in progress, minor bugs";
    position: absolute;
    right: 10px;
    top: 50%;
    font-weight: bold;
    color: #fff;
    transform: translateY(-50%);
  }
  #app-mount .members-1998pB>div {
    background: transparent;
  }
  #app-mount .member-3-YXUe {
    padding-right: 0;
    max-width: 100%;
    border-radius: 0;
  }
  #app-mount .member-3-YXUe .layout-2DM8Md {
    border-radius: 5px 0 0 5px;
  }
  #app-mount .member-3-YXUe:hover .layout-2DM8Md {
    background: var(--channel-hovered-bg);
  }
  #app-mount .member-3-YXUe.selected-aXhQR6 .layout-2DM8Md {
    background: var(--channel-selected-bg);
    box-shadow: inset -4px 0 0 rgba(var(--accent), 1);
  }
  #app-mount .members-1998pB {
    background: transparent;
  }
  #app-mount .members-1998pB::-webkit-scrollbar {
    display: none;
  }
  #app-mount .container-3Mxszk .scroller-1IIF0A {
    background: var(--background-1);
  }
  #app-mount .applicationStore-1pNvnv {
    background: var(--background-1);
  }
  #app-mount .applicationStore-1pNvnv .container-xm7Ad0:before {
    content: none;
  }
  #app-mount .applicationStore-1pNvnv .scroller-9moviB {
    background-color: transparent;
  }
  #app-mount .applicationStore-1pNvnv .detailsBlock-FoDTGA {
    background-color: var(--pages-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .applicationStore-1pNvnv .tier1Banner-1B_WXY {
    background-color: var(--pages-box);
    background-image: none;
    box-shadow: var(--box-shadow);
  }
  #app-mount .applicationStore-1pNvnv .gradientOverlayLeft-3w159C {
    background: linear-gradient(90deg, var(--background-1), transparent);
  }
  #app-mount .applicationStore-1pNvnv .gradientOverlayRight-3vMuS8 {
    background: linear-gradient(90deg, transparent, var(--background-1));
  }
  #app-mount .applicationStore-1pNvnv .tile-QA_yMc {
    background-color: var(--pages-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .applicationStore-1pNvnv .arrow-15GutB {
    background: var(--pages-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .container-1D34oG {
    background: var(--background-1);
  }
  #app-mount .tabBody-3YRQ8W:before {
    content: none;
  }
  #app-mount .peopleListItem-2nzedh {
    border-radius: 3px;
  }
  #app-mount .peopleListItem-2nzedh:hover {
    background: var(--background-2);
  }
  #app-mount .nowPlayingColumn-2sl4cE {
    background: var(--background-2);
  }
  #app-mount .nowPlayingColumn-2sl4cE .emptyCard-1RJw8n {
    background: var(--background-1);
    box-shadow: var(--box-shadow);
  }
  #app-mount .nowPlayingColumn-2sl4cE .wrapper-3D2qGf {
    background: var(--dropdown);
  }
  #app-mount .nowPlayingColumn-2sl4cE .wrapper-3D2qGf .inset-3sAvek {
    background: rgba(0, 0, 0, 0.2);
  }
  #app-mount .pageWrapper-1PgVDX {
    background-color: var(--background-1);
  }
  #app-mount .pageWrapper-1PgVDX .bg-AYqtMd {
    display: none;
  }
  #app-mount .pageWrapper-1PgVDX .card-3DjzTQ {
    border-radius: 5px;
  }
  #app-mount .pageWrapper-1PgVDX .card-3DjzTQ, #app-mount .pageWrapper-1PgVDX .css-1wqqa50-container, #app-mount .pageWrapper-1PgVDX .searchBox-3Y2Vi7 {
    background-color: var(--pages-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .searchBar-3dMhjb {
    background: var(--background-2);
  }
  #app-mount .searchBar-3dMhjb .searchAnswer-3Dz2-q,
  #app-mount .searchBar-3dMhjb .searchFilter-2ESiM3 {
    background-color: var(--foreground-1);
    color: var(--text-1);
  }
  #app-mount .container-3ayLPN {
    background-color: var(--dropdown);
    box-shadow: var(--box-shadow);
  }
  #app-mount .container-3ayLPN .displayedNick-3xxvzU,
  #app-mount .container-3ayLPN .filter-3Y_im-,
  #app-mount .container-3ayLPN .header-2N-gMV {
    color: var(--text-1);
  }
  #app-mount .container-3ayLPN .answer-1n6g43,
  #app-mount .container-3ayLPN .displayUsername-Qekxml {
    color: var(--text-3);
  }
  #app-mount .container-3ayLPN .option-96V44q.selected-rZcOL- {
    background-color: var(--search-filter-hover);
  }
  #app-mount .container-3ayLPN .option-96V44q.selected-rZcOL- .plusIcon-v0BTrL {
    color: var(--text-1);
    opacity: 1;
  }
  #app-mount .container-3ayLPN .option-96V44q.selected-rZcOL-:after {
    background: linear-gradient(90deg, transparent, var(--search-filter-hover) 80%);
  }
  #app-mount .container-3ayLPN .option-96V44q:after {
    background: transparent;
  }
  #app-mount .container-3ayLPN .react-datepicker {
    background-color: var(--background-3);
    border-radius: 0;
  }
  #app-mount .container-3ayLPN .react-datepicker__header {
    background-color: Var(--background-3);
  }
  #app-mount .container-3ayLPN .react-datepicker__day {
    background-color: var(--background-4);
  }
  #app-mount .container-3ayLPN .react-datepicker__day--disabled,
  #app-mount .container-3ayLPN .react-datepicker__day--outside-month {
    background-color: var(--background-1);
  }
  #app-mount .searchResultsWrap-3-pOjs {
    background: var(--background-1);
  }
  #app-mount .searchResult-9tQ1uo:before, #app-mount .searchResult-9tQ1uo:after {
    content: none;
  }
  #app-mount .searchResultMessage-1fxgXh.hit-1fVM9e {
    box-shadow: var(--box-shadow);
    border: none;
    background: var(--message-box);
  }
  #app-mount .embedFull-2tM8-- {
    background: var(--background-1);
  }
  #app-mount .channelName-1JRO3C {
    background: var(--background-1);
  }
  #app-mount .layer-v9HyYc[style*=left][style*=top] .menu-Sp6bN1 {
    background: var(--dropdown);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-v9HyYc[style*=left][style*=top] .menu-Sp6bN1 .item-1GzJrl:not(.invite-271nFU):not(.leave-1DRJfn) {
    color: var(--text-2);
  }
  #app-mount .layer-v9HyYc[style*=left][style*=top] .menu-Sp6bN1 .item-1GzJrl:not(.invite-271nFU):not(.leave-1DRJfn):hover {
    color: var(--text-1) !important;
  }
  #app-mount .layer-v9HyYc[style*=left][style*=top] .menu-Sp6bN1 .item-1GzJrl:first-child .label-1Y-LW5 {
    color: var(--nitro);
  }
  #app-mount .layer-v9HyYc[style*=left][style*=top] .menu-Sp6bN1 .item-1GzJrl:hover {
    background-color: var(--dropdown-item-hover);
  }
  #app-mount .layer-v9HyYc[style*=left][style*=bottom] .menu-Sp6bN1 {
    background: var(--dropdown);
    box-shadow: var(--box-shadow);
  }
  #app-mount .layer-v9HyYc[style*=left][style*=bottom] .menu-Sp6bN1 .itemBase-1Qj4z6:hover {
    background-color: var(--dropdown-item-hover);
    color: var(--text-1);
  }
  #app-mount .userPopout-3XzG_A {
    box-shadow: var(--box-shadow);
    background: var(--user-popout);
  }
  #app-mount .userPopout-3XzG_A .header-2BwW8b .headerName-fajvi9,
  #app-mount .userPopout-3XzG_A .header-2BwW8b .headerTag-2pZJzA,
  #app-mount .userPopout-3XzG_A .header-2BwW8b .headerTagUsernameNoNickname-2_H881 {
    color: var(--text-1);
  }
  #app-mount .userPopout-3XzG_A .headerNormal-T_seeN,
  #app-mount .userPopout-3XzG_A .headerPlaying-j0WQBV {
    background: transparent;
  }
  #app-mount .userPopout-3XzG_A .headerSpotify-zpWxgT {
    background: transparent;
  }
  #app-mount .userPopout-3XzG_A .headerSpotify-zpWxgT .lookOutlined-3sRXeN.colorWhite-rEQuAQ {
    background: var(--spotify-green);
    color: #fff;
    border: none;
  }
  #app-mount .userPopout-3XzG_A .headerSpotify-zpWxgT .lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover {
    background: var(--spotify-green-dark);
  }
  #app-mount .userPopout-3XzG_A .headerStreaming-2FjmGz {
    background: transparent;
  }
  #app-mount .userPopout-3XzG_A .headerStreaming-2FjmGz .lookOutlined-3sRXeN.colorWhite-rEQuAQ {
    background: var(--twitch-purple);
    border: none;
  }
  #app-mount .userPopout-3XzG_A .headerStreaming-2FjmGz .lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover {
    background: var(--twitch-purple-dark);
  }
  #app-mount .userPopout-3XzG_A .activity-11LB_k {
    background: transparent;
  }
  #app-mount .userPopout-3XzG_A .activity-11LB_k .activityName-1IaRLn,
  #app-mount .userPopout-3XzG_A .activity-11LB_k .headerText-1HLrL7 {
    color: var(--text-1);
  }
  #app-mount .userPopout-3XzG_A .activity-11LB_k .content-3JfFJh {
    color: var(--text-2);
  }
  #app-mount .userPopout-3XzG_A .body-3iLsc4 {
    background: var(--user-popout-body);
    padding: 10px;
  }
  #app-mount .userPopout-3XzG_A .body-3iLsc4::-webkit-scrollbar {
    display: none;
  }
  #app-mount .userPopout-3XzG_A .textRow-19NEd_ {
    color: var(--text-1);
  }
  #app-mount .userPopout-3XzG_A .addButton-pcyyf6 {
    position: absolute;
    top: 7px;
    right: 6px;
    border: none;
  }
  #app-mount .userPopout-3XzG_A .addButton-pcyyf6:hover {
    color: var(--text-1);
  }
  #app-mount .userPopout-3XzG_A .customStatus-1bh2V9 {
    color: var(--text-1);
  }
  #app-mount .userPopout-3XzG_A .bodyTitle-Y0qMQz {
    color: var(--text-1);
  }
  #app-mount .userPopout-3XzG_A .note-3HfJZ5 {
    margin-left: 0;
    position: relative;
  }
  #app-mount .userPopout-3XzG_A .note-3HfJZ5 textarea {
    max-height: unset;
  }
  #app-mount .userPopout-3XzG_A .note-3HfJZ5 textarea:focus {
    background: var(--user-popout-message);
  }
  #app-mount .userPopout-3XzG_A .note-3HfJZ5 .charcounter.popout {
    bottom: unset !important;
    top: -19px;
  }
  #app-mount .userPopout-3XzG_A .footer-1fjuF6 {
    background: var(--user-popout-body);
    border: none;
    padding: 0;
  }
  #app-mount .userPopout-3XzG_A .footer-1fjuF6 .input-cIJ7To {
    background: var(--user-popout-message);
    border: none;
    margin: 0 10px 10px;
    box-sizing: border-box;
    width: calc(100% - 20px);
  }
  #app-mount .userPopout-3XzG_A .footer-1fjuF6 .input-cIJ7To::placeholder {
    text-transform: uppercase;
    font-weight: bold;
    letter-spacing: 1.5px;
    font-size: 12px;
    opacity: 0.7;
  }
  #app-mount .userPopout-3XzG_A .footer-1fjuF6 .protip-YaFfgO {
    display: none;
  }
  .theme-light .userPopout-3XzG_A [mask*="url(#svg-mask-status-online)"] {
    fill: var(--text-1) !important;
  }
  .theme-light .userPopout-3XzG_A [mask*="url(#svg-mask-status-dnd)"] {
    fill: var(--red);
  }
  .theme-light .userPopout-3XzG_A .headerPlaying-j0WQBV .profileBadgeHypeSquadOnlineHouse2-3jBpXR,
  .theme-light .userPopout-3XzG_A .headerPlaying-j0WQBV .profileBadgePremium-3kZ9Qj,
  .theme-light .userPopout-3XzG_A .headerPlaying-j0WQBV .profileBadgeEarlySupporter-PQB_0a,
  .theme-light .userPopout-3XzG_A .headerPlaying-j0WQBV [class*=BadgeHype], .theme-light .userPopout-3XzG_A .headerSpotify-zpWxgT .profileBadgeHypeSquadOnlineHouse2-3jBpXR,
  .theme-light .userPopout-3XzG_A .headerSpotify-zpWxgT .profileBadgePremium-3kZ9Qj,
  .theme-light .userPopout-3XzG_A .headerSpotify-zpWxgT .profileBadgeEarlySupporter-PQB_0a,
  .theme-light .userPopout-3XzG_A .headerSpotify-zpWxgT [class*=BadgeHype] {
    filter: invert(1);
  }
  #app-mount .styleFlexible-wGDiIL,
  #app-mount .submenu-2-ysNh {
    background: var(--dropdown);
  }
  #app-mount .barFill-23-gu- {
    background: rgb(var(--accent));
  }
  #app-mount .autocomplete-1vrmpx {
    background: var(--dropdown);
    box-shadow: var(--box-shadow);
  }
  #app-mount .autocomplete-1vrmpx .selectorSelected-1_M1WV {
    background-color: var(--dropdown-item-hover);
  }
  #app-mount .autocomplete-1vrmpx .container-cMG81i {
    background-color: var(--background-1);
  }
  #app-mount .autocomplete-1vrmpx .focused-1En8bG:after,
  #app-mount .autocomplete-1vrmpx .result-3w1ZcL:hover:after {
    box-shadow: inset 0 0 0 2px rgba(var(--accent), 1);
  }
  #app-mount .autocomplete-1vrmpx .categoryFadeBlurple-1j72_A {
    background: rgba(var(--accent), 0.5);
  }
  #app-mount .messagesPopoutWrap-1MQ1bW {
    background-color: var(--dropdown);
    box-shadow: var(--box-shadow);
    border: none;
  }
  #app-mount .messagesPopoutWrap-1MQ1bW .header-ykumBX {
    background-color: var(--dropdown-header);
    box-shadow: var(--box-shadow);
  }
  #app-mount .messagesPopoutWrap-1MQ1bW .container-3iAQ-0 {
    padding: 10px;
    box-sizing: border-box;
    margin: 10px 10px 0 10px;
    border-radius: 5px;
    background: var(--dropdown-item-hover);
  }
  #app-mount .messagesPopoutWrap-1MQ1bW .channelHeader-3Gd2xq {
    background: transparent;
  }
  #app-mount .messagesPopoutWrap-1MQ1bW .messageContainer-gbhlwo {
    background: var(--dropdown);
  }
  #app-mount .messagesPopoutWrap-1MQ1bW .button-1-5Aqk {
    background: var(--message-button);
  }
  #app-mount .layer-v9HyYc[style*=left][style*=bottom] .container-2x5lvQ {
    background: var(--dropdown);
    box-shadow: var(--box-shadow);
    border-radius: 3px;
  }
  #app-mount .layer-v9HyYc[style*=left][style*=bottom] .container-2x5lvQ header {
    background: var(--dropdown-header);
  }
  #app-mount .layer-v9HyYc[style*=left][style*=bottom] .container-2x5lvQ section {
    background-color: transparent;
  }
  #app-mount .emojiPicker-3m1S-j {
    background: var(--dropdown);
    box-shadow: var(--box-shadow);
  }
  #app-mount .emojiPicker-3m1S-j .scroller-3vODG7 {
    height: var(--emoji-picker-height);
  }
  #app-mount .emojiPicker-3m1S-j .searchBar-2pWH0_ {
    background: var(--dropdown-header);
  }
  #app-mount .emojiPicker-3m1S-j .infoBar-U6oBFk {
    background: var(--dropdown);
    box-shadow: var(--box-shadow);
  }
  #app-mount .emojiPicker-3m1S-j .stickyHeader-1SS0JU {
    background: var(--dropdown);
    opacity: 1;
  }
  #app-mount .emojiPicker-3m1S-j .categories-1feg4n {
    background: var(--dropdown-header);
  }
  #app-mount .emojiPicker-3m1S-j .popout-2nUePc {
    background: var(--dropdown);
    box-shadow: var(--box-shadow);
  }
  #app-mount .popoutList-T9CKZQ {
    background: var(--dropdown);
    padding: 0;
  }
  #app-mount .popoutList-T9CKZQ .container-cMG81i {
    background: var(--dropdown-header);
    border-radius: 4px 4px 0 0;
  }
  #app-mount .popoutList-T9CKZQ .container-cMG81i .inner-2P4tQO {
    padding: 0 10px 0 0;
    display: flex;
    align-items: center;
  }
  #app-mount .popoutList-T9CKZQ .container-cMG81i .inner-2P4tQO input {
    padding: 10px;
    height: auto;
  }
  #app-mount .popoutList-T9CKZQ .divider-3573oO {
    display: none;
  }
  #app-mount .container-VSDcQc .autocompleteShadow-iiGWFU {
    box-shadow: var(--box-shadow);
    background: var(--user-popout);
  }
  #app-mount .container-VSDcQc .autocompleteArrow-Zxoy9H {
    box-shadow: var(--box-shadow);
    background: var(--user-popout);
  }
  #app-mount .container-VSDcQc .header-2bNvm4 {
    background: var(--user-popout-body);
  }
  #app-mount .container-VSDcQc .sectionTag-pXyto9 {
    background: var(--user-popout);
  }
  #app-mount .container-VSDcQc .row-rrHHJU.selected-1pIgLL {
    background: rgba(255, 255, 255, 0.02);
  }
  #app-mount .recentMentionsPopout-3rCiI6 {
    background: var(--dropdown);
  }
  #app-mount .recentMentionsPopout-3rCiI6 .header-2-Imhb {
    background: var(--dropdown-header);
  }
  #app-mount .modal-yWgWj- {
    background: var(--background-1);
  }
  #app-mount .modal-yWgWj- .footer-3rDWdC {
    background-color: var(--background-2);
    box-shadow: none;
    border: none;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa {
    background: transparent;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa [class*=topSection] .headerFill-adLl4x {
    background: transparent;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa [class*=topSection]:not([class*=SectionNormal]) .profileBadge-2BqF-Z {
    filter: var(--modal-badge-invert);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionNormal-2-vo2m {
    background: var(--background-1);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionPlaying-1J5E4n {
    background: var(--background-1);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionPlaying-1J5E4n .lookInverted-2D7oAl.colorBrand-3pXr91 {
    background: var(--blurple);
    color: #fff;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .tabBarContainer-1s1u-z {
    border: none;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .activityProfile-2bJRaP {
    position: relative;
    cursor: pointer;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .activityProfile-2bJRaP .headerTextNormal-2mGWX3 {
    margin-bottom: 0;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .activityProfile-2bJRaP .body-ZAhrcj {
    max-height: 0;
    overflow: hidden;
    transition: 0.4s ease;
    transition-delay: 0s;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .activityProfile-2bJRaP:after {
    content: "";
    width: 8px;
    height: 8px;
    border-left: 1px solid var(--text-1);
    border-bottom: 1px solid var(--text-1);
    display: block;
    position: absolute;
    right: 25px;
    top: 23px;
    transform: rotate(-135deg);
    transition: 0.4s ease;
    transition-delay: 0s;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .activityProfile-2bJRaP:hover .body-ZAhrcj {
    max-height: 130px;
    margin-top: 10px;
    transition-delay: 0.3s;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .activityProfile-2bJRaP:hover:after {
    transform: rotate(-45deg);
    transition-delay: 0.3s;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionSpotify-1lI0-P {
    background: var(--background-1);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionSpotify-1lI0-P .lookInverted-2D7oAl.colorGreen-29iAKY,
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionSpotify-1lI0-P .lookOutlined-3sRXeN.colorWhite-rEQuAQ {
    background: var(--spotify-green);
    color: #fff;
    border: none;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionSpotify-1lI0-P .lookInverted-2D7oAl.colorGreen-29iAKY:hover,
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionSpotify-1lI0-P .lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover {
    background: var(--spotify-green-dark);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionSpotify-1lI0-P .bar-3urHkF {
    background-color: var(--text-dark);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .topSectionSpotify-1lI0-P .bar-3urHkF .barInner-3NDaY_ {
    background-color: var(--text-1);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .username-3gJmXY {
    color: var(--text-1);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .activityHeader-1PExlk,
  #app-mount .modal-3c3bKg .root-SR8cQa .activityName-1IaRLn,
  #app-mount .modal-3c3bKg .root-SR8cQa .additionalActionsIcon-1FoUlE,
  #app-mount .modal-3c3bKg .root-SR8cQa .contentGameImageProfile-WTVbI0,
  #app-mount .modal-3c3bKg .root-SR8cQa .customStatusText-39gdCI,
  #app-mount .modal-3c3bKg .root-SR8cQa .discriminator-xUhQkU,
  #app-mount .modal-3c3bKg .root-SR8cQa .headerText-1HLrL7,
  #app-mount .modal-3c3bKg .root-SR8cQa .text-AOoUen,
  #app-mount .modal-3c3bKg .root-SR8cQa .textRow-19NEd_ {
    color: var(--text-1);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .tabBarItem-1b8RUP {
    color: var(--text-1) !important;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .tabBarItem-1b8RUP[style]:not([style*="border-color: transparent"]) {
    border-color: var(--text-1) !important;
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .body-3ND3kc {
    background: var(--background-2);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .body-3ND3kc .connectedAccount-36nQx7 {
    background: var(--modal-connection);
    border: none;
    box-shadow: var(--box-shadow);
  }
  #app-mount .modal-3c3bKg .root-SR8cQa .body-3ND3kc .listRow-hutiT_:hover {
    background: var(--modal-list);
  }
  #app-mount .uploadModal-2ifh8j {
    background-color: var(--background-1);
  }
  #app-mount .uploadModal-2ifh8j .inner-3nWsbo {
    margin: 0;
  }
  #app-mount .uploadModal-2ifh8j .comment-4IWttf {
    margin: 0;
    padding: 0 20px 20px;
    box-sizing: border-box;
  }
  #app-mount .uploadModal-2ifh8j .comment-4IWttf .inner-zqa7da {
    background-color: var(--background-2);
  }
  #app-mount .uploadModal-2ifh8j .channelTextAreaUpload-3t7EIx {
    margin: 5px 0 0;
  }
  #app-mount .uploadModal-2ifh8j .channelTextAreaUpload-3t7EIx .scrollableContainer-2NUZem {
    background-color: var(--foreground-1);
  }
  #app-mount .uploadModal-2ifh8j .channelTextAreaUpload-3t7EIx .charCounter-7fw40k.charcounter {
    bottom: unset;
    top: -18px;
  }
  #app-mount .uploadModal-2ifh8j .footer-3mqk7D {
    background-color: var(--background-2);
    box-shadow: none;
  }
  #app-mount .uploadModal-2ifh8j .footer-3mqk7D .checked-3_4uQ9[style*="rgb(114, 137, 218)"] {
    border-color: rgba(var(--accent), 1) !important;
    background: rgba(var(--accent), 1) !important;
  }
  #app-mount .uploadModal-2ifh8j .footer-3mqk7D .checked-3_4uQ9[style*="rgb(114, 137, 218)"] polyline {
    stroke: #fff;
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS {
    background-color: var(--background-1);
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS .item-26Dhrx[style*="rgb(114, 137, 218)"] {
    background: rgba(var(--accent), 1) !important;
    border-color: rgba(var(--accent), 1) !important;
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS .checkboxMute-14hTGS:before {
    background-color: var(--background-2);
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS .cardPrimaryEditable-3KtE4g {
    background: var(--background-2);
    border-color: var(--background-2);
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS .cardPrimaryEditable-3KtE4g .checked-3_4uQ9 {
    border-color: #fff !important;
    background-color: #fff !important;
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS .cardPrimaryEditable-3KtE4g .checked-3_4uQ9 polyline {
    stroke: rgba(var(--accent), 1);
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS .checked-3_4uQ9 {
    border-color: rgba(var(--accent), 1) !important;
    background-color: rgba(var(--accent), 1) !important;
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS .checked-3_4uQ9 polyline {
    stroke: #fff;
  }
  #app-mount .modal-yWgWj-.sizeMedium-df47zS .footer-3rDWdC {
    background-color: var(--background-2);
    box-shadow: none;
  }
  #app-mount .wrapper-2ZbzR9 .input-1mgnkM,
  #app-mount .wrapper-2ZbzR9 .input-UJ9Tr3 {
    border: none;
    padding: 10px;
    box-sizing: border-box;
    border-radius: 5px;
  }
  #app-mount .wrapper-2ZbzR9 .regionSelect-3lf4eE:hover {
    box-shadow: none;
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU {
    background-image: none;
    padding: 30px;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU .header-3ZP1MY {
    margin-top: 0;
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU .actions-pBaxX6 .action-1lSjCi {
    width: 50%;
    box-shadow: var(--box-shadow);
    padding: 0 10px 10px;
    border: none;
    transition: 0.2s ease;
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU .actions-pBaxX6 .action-1lSjCi .actionIcon-2IISM_ {
    background-image: none;
    transition: 0.2s ease;
    filter: none;
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU .actions-pBaxX6 .action-1lSjCi.create-3jownz .actionIcon-2IISM_ {
    -webkit-mask: url('data:image/svg+xml; utf-8, <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="plus" class="svg-inline--fa fa-plus fa-w-14" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="currentColor" d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z"></path></svg>') center/64px no-repeat;
    background: var(--blurple);
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU .actions-pBaxX6 .action-1lSjCi.create-3jownz:hover .actionIcon-2IISM_ {
    background: var(--blurpleDark);
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU .actions-pBaxX6 .action-1lSjCi.join-33Tr-7 .actionIcon-2IISM_ {
    -webkit-mask: url('data:image/svg+xml; utf-8, <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="long-arrow-alt-right" class="svg-inline--fa fa-long-arrow-alt-right fa-w-14" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"><path fill="currentColor" d="M313.941 216H12c-6.627 0-12 5.373-12 12v56c0 6.627 5.373 12 12 12h301.941v46.059c0 21.382 25.851 32.09 40.971 16.971l86.059-86.059c9.373-9.373 9.373-24.569 0-33.941l-86.059-86.059c-15.119-15.119-40.971-4.411-40.971 16.971V216z"></path></svg>') center/64px no-repeat;
    background: var(--green);
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU .actions-pBaxX6 .action-1lSjCi.join-33Tr-7:hover .actionIcon-2IISM_ {
    background: var(--greenDark);
  }
  #app-mount .wrapper-2ZbzR9 .slideBody-2nMrnU .actions-pBaxX6 .or-3THJsp {
    display: none;
  }
  html.theme-dark .theme-light .wrapper-2ZbzR9 {
    background: var(--dark-modal-background) !important;
  }
  html.theme-dark .theme-light .wrapper-2ZbzR9 .slide-2pHaq5 {
    background: var(--dark-modal-background) !important;
  }
  html.theme-dark .theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .description-QF3836 {
    color: #bbb !important;
  }
  html.theme-dark .theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .regionSelect-3lf4eE button,
  html.theme-dark .theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .regionSelectInner-24f4Ce {
    background: var(--dark-modal-footer) !important;
    border: none !important;
  }
  html.theme-dark .theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .input-1mgnkM,
  html.theme-dark .theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .input-UJ9Tr3 {
    background: var(--dark-modal-footer) !important;
    color: #fff !important;
  }
  html.theme-dark .theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .action-1lSjCi {
    background: var(--dark-modal-item) !important;
  }
  html.theme-dark .theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .footer-3rDWdC {
    background: var(--dark-modal-footer) !important;
  }
  html.theme-light .wrapper-2ZbzR9 {
    background: var(--light-modal-background) !important;
  }
  html.theme-light .wrapper-2ZbzR9 .slide-2pHaq5 {
    background: var(--light-modal-background) !important;
  }
  html.theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .description-QF3836 {
    color: #444 !important;
  }
  html.theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .regionSelect-3lf4eE button,
  html.theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .regionSelectInner-24f4Ce {
    background: var(--light-modal-footer) !important;
    border: none !important;
  }
  html.theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .input-1mgnkM,
  html.theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .input-UJ9Tr3 {
    background: var(--light-modal-footer) !important;
    color: #000 !important;
  }
  html.theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .action-1lSjCi {
    background: var(--light-modal-item) !important;
  }
  html.theme-light .wrapper-2ZbzR9 .slide-2pHaq5 .footer-3rDWdC {
    background: var(--light-modal-footer) !important;
  }
  #app-mount .regionSelectModal-12e-57 {
    background: var(--background-2);
  }
  #app-mount .regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3 {
    background: var(--background-1);
    border: none;
    box-shadow: var(--box-shadow);
  }
  #app-mount .modal-3c3bKg .inner-1ilYF7 {
    display: block;
  }
  #app-mount .modal-3c3bKg .inner-1ilYF7 .downloadLink-1ywL9o {
    margin-right: 10px;
  }
  #app-mount .modal-3c3bKg .inner-1ilYF7 .downloadLink-1ywL9o+span.downloadLink-1ywL9o {
    display: none;
  }
  #app-mount .modal-3c3bKg .inner-1ilYF7 .downloadLink-1ywL9o:last-child {
    margin-right: 10px;
  }
  #app-mount .modal-3c3bKg .inner-1ilYF7 .downloadLink-1ywL9o:hover {
    color: var(--text-1) !important;
  }
  #app-mount .container-3qKHyN {
    height: auto;
  }
  #app-mount .quickswitcher-3JagVE {
    background-color: var(--background-1);
    box-shadow: var(--box-shadow);
    padding: 0;
  }
  #app-mount .quickswitcher-3JagVE .input-2VB9rf {
    margin: 20px 20px 0;
    box-sizing: border-box;
    padding: 0 20px;
    background: var(--modal-bg1-search);
    box-shadow: var(--box-shadow);
  }
  #app-mount .quickswitcher-3JagVE .input-2VB9rf::placeholder {
    color: var(--text-1);
    opacity: 0.4;
  }
  #app-mount .quickswitcher-3JagVE .scroller-zPkAnE {
    background: transparent;
    padding: 20px 30px 20px 20px;
    box-sizing: border-box;
  }
  #app-mount .quickswitcher-3JagVE .scroller-zPkAnE>div[style*="height: 15px"] {
    display: none;
  }
  #app-mount .quickswitcher-3JagVE .resultFocused-3aIoYe {
    background: var(--background-2);
  }
  #app-mount .quickswitcher-3JagVE .tipsWithResults-HhTE9b {
    padding: 20px;
    box-sizing: border-box;
    background: var(--background-2);
    border: none;
  }
  #app-mount .root-1gCeng {
    background: var(--background-1);
  }
  #app-mount .root-1gCeng .input-1GLP_D, #app-mount .root-1gCeng .lookFilled-1h1y05.select-1Pkeg4 {
    background-color: var(--background-2);
    border: none;
  }
  #app-mount .root-1gCeng .footer-3rDWdC {
    background: var(--background-2);
    box-shadow: none;
  }
  #app-mount .modal-yWgWj- .message-2qRu38 {
    background: var(--message-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .wrapper-3vR61M,
  #app-mount .wrapper-1F5TKx {
    background: transparent;
  }
  #app-mount .chat-3bRxxu {
    background: var(--background-1);
  }
  #app-mount .chat-3bRxxu .scroller-2FKFPG {
    background: transparent;
  }
  #app-mount .chat-3bRxxu .content-yTz4x3:before {
    content: none;
  }
  #app-mount .messagesWrapper-3lZDfY ::-webkit-scrollbar-thumb {
    visibility: hidden !important;
  }
  #app-mount .messagesWrapper-3lZDfY:hover ::-webkit-scrollbar-thumb {
    visibility: visible !important;
  }
  #app-mount .jumpToPresentBar-9P20AM {
    left: unset;
    bottom: 20px;
    right: 16px;
    padding: 0 10px 0 5px;
    background: var(--message-button);
    box-shadow: var(--box-shadow), 0 0 5px rgba(0, 0, 0, 0.3);
    border-radius: 5px;
    opacity: 1;
  }
  #app-mount .jumpToPresentBar-9P20AM>span {
    padding: 0 0 0 5px;
  }
  #app-mount .jumpToPresentBar-9P20AM>span .spinnerItem-2r0Owh {
    background-color: var(--text-1);
  }
  #app-mount .jumpToPresentBar-9P20AM button {
    font-size: 12px;
    padding-right: 0;
    height: auto;
    color: var(--text-1);
  }
  #app-mount .jumpToPresentBar-9P20AM button svg {
    display: none;
  }
  #app-mount .jumpToPresentBar-9P20AM button:first-child {
    display: none;
  }
  #app-mount .jumpToPresentBar-9P20AM:before {
    content: "";
    width: 16px;
    height: 16px;
    -webkit-mask: url('data:image/svg+xml; utf-8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M0 0h24v24H0z" fill="none"/><path d="M13 3c-4.97 0-9 4.03-9 9H1l3.89 3.89.07.14L9 12H6c0-3.87 3.13-7 7-7s7 3.13 7 7-3.13 7-7 7c-1.93 0-3.68-.79-4.94-2.06l-1.42 1.42C8.27 19.99 10.51 21 13 21c4.97 0 9-4.03 9-9s-4.03-9-9-9zm-1 5v5l4.28 2.54.72-1.21-3.5-2.08V8H12z"/></svg>') center/cover;
    background: var(--text-1);
  }
  #app-mount .newMessagesBar-mujexs {
    top: 10px;
    left: 30px;
    right: 30px;
    border-radius: 5px;
    box-shadow: var(--box-shadow);
    background: rgba(var(--accent), 1);
  }
  #app-mount .divider-JfaTT5 {
    border: none;
    height: auto;
    margin: 15px 0 15px 16px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    top: 0;
  }
  #app-mount .divider-JfaTT5 span {
    margin-right: 0;
    position: unset;
    padding: 0;
    background: transparent;
    font-size: 16px;
  }
  #app-mount .divider-JfaTT5 span.content-1o0f9g+.unreadPill-2HyYtt {
    margin-left: 10px;
  }
  #app-mount .divider-JfaTT5 span.unreadPill-2HyYtt {
    color: var(--red);
    height: auto;
  }
  #app-mount .divider-JfaTT5 svg {
    display: none;
  }
  #app-mount .divider-JfaTT5+.cozyMessage-3V1Y8y.groupStart-23k01U {
    margin-top: 0;
  }
  #app-mount .cozyMessage-3V1Y8y {
    background: var(--message-box);
    margin: 0 8px 0 16px;
    padding: var(--message-padding);
  }
  #app-mount .cozyMessage-3V1Y8y .avatar-1BDn8e {
    top: var(--message-padding);
    left: var(--message-padding);
  }
  #app-mount .cozyMessage-3V1Y8y .avatar-1BDn8e+h2 {
    margin-left: 0;
    padding-left: 0;
  }
  #app-mount .cozyMessage-3V1Y8y .contents-2mQqc9,
  #app-mount .cozyMessage-3V1Y8y .container-1ov-mD {
    padding-left: calc(var(--message-padding) + 38px);
    padding-bottom: 0;
  }
  #app-mount .cozyMessage-3V1Y8y .embedFull-2tM8-- {
    background: var(--message-embed);
  }
  #app-mount .cozyMessage-3V1Y8y .container-3npvBV {
    transform: scale(0.8);
    padding-right: 0;
  }
  #app-mount .cozyMessage-3V1Y8y .wrapper-2aW0bm {
    background: var(--foreground-1);
    box-shadow: var(--box-shadow);
  }
  #app-mount .cozyMessage-3V1Y8y .scrollableContainer-2NUZem {
    background: var(--background-1);
    box-shadow: none;
  }
  #app-mount .cozyMessage-3V1Y8y.groupStart-23k01U {
    margin-top: var(--message-spacing);
  }
  #app-mount .cozyMessage-3V1Y8y+.cozyMessage-3V1Y8y:not(.groupStart-23k01U) {
    margin-top: calc(var(--message-padding) / -1);
    padding-top: 3px;
  }
  #app-mount .cozyMessage-3V1Y8y.mentioned-xhSam7:before {
    content: none;
  }
  #app-mount .cozyMessage-3V1Y8y.mentioned-xhSam7 .contents-2mQqc9 {
    position: relative;
  }
  #app-mount .cozyMessage-3V1Y8y.mentioned-xhSam7 .contents-2mQqc9 .avatar-1BDn8e {
    top: 0;
    left: 0;
  }
  #app-mount .cozyMessage-3V1Y8y.mentioned-xhSam7 .contents-2mQqc9 .channelTextArea-2VhZ6z,
  #app-mount .cozyMessage-3V1Y8y.mentioned-xhSam7 .contents-2mQqc9 .operations-36ENbA {
    position: relative;
    z-index: 1;
  }
  #app-mount .cozyMessage-3V1Y8y.mentioned-xhSam7 .contents-2mQqc9:before {
    content: "";
    position: absolute;
    display: block;
    top: 0;
    left: calc(var(--message-padding) / -1);
    bottom: 0;
    pointer-events: none;
    width: 2px;
    background-color: #faa61a;
  }
  #app-mount .cozyMessage-3V1Y8y.mentioned-xhSam7 .contents-2mQqc9:after {
    content: "";
    position: absolute;
    top: 0;
    left: calc(var(--message-padding) / -1);
    width: calc(100% + var(--message-padding) * 2);
    height: 100%;
    background: rgba(250, 166, 26, 0.05);
    z-index: 0;
    pointer-events: none;
  }
  #app-mount .channelTextArea-rNsIhG {
    border-top-color: var(--message-box-divider);
    background: transparent;
  }
  #app-mount .form-2fGMdU:before {
    content: none;
  }
  #app-mount .inner-MADQqc {
    max-height: 144px;
  }
  #app-mount .buttons-3JBrkn {
    height: 54px;
  }
  #app-mount .buttons-3JBrkn button {
    opacity: 0.3;
    min-height: 54px;
  }
  #app-mount .buttons-3JBrkn button:hover {
    opacity: 1;
  }
  #app-mount .attachWrapper-2TRKBi {
    border-right: none;
  }
  #app-mount .attachButton-2WznTc {
    height: 100%;
  }
  #app-mount .attachButton-2WznTc .attachButtonInner-PQjIyk {
    display: none;
  }
  #app-mount .attachButton-2WznTc:before {
    content: "";
    width: 24px;
    height: 24px;
    background: var(--text-normal);
    -webkit-mask: url('data:image/svg+xml; utf-8,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M16.5 6v11.5c0 2.21-1.79 4-4 4s-4-1.79-4-4V5c0-1.38 1.12-2.5 2.5-2.5s2.5 1.12 2.5 2.5v10.5c0 .55-.45 1-1 1s-1-.45-1-1V6H10v9.5c0 1.38 1.12 2.5 2.5 2.5s2.5-1.12 2.5-2.5V5c0-2.21-1.79-4-4-4S7 2.79 7 5v12.5c0 3.04 2.46 5.5 5.5 5.5s5.5-2.46 5.5-5.5V6h-1.5z"/><path d="M0 0h24v24H0z" fill="none"/></svg>') center/20px no-repeat;
    opacity: 0.3;
    transition: 0.2s ease;
  }
  #app-mount .attachButton-2WznTc:hover:before {
    opacity: 1;
    -webkit-mask-size: 24px;
  }
  #app-mount .operations-36ENbA>a {
    color: rgba(var(--accent), 1);
  }
  #app-mount .attachButtonDivider-3Glu60 {
    display: none;
  }
  #app-mount .scrollableContainer-2NUZem {
    background-color: var(--message-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .textArea-12jD-V {
    padding: 15px;
    box-sizing: border-box;
    top: 1px;
  }
  #app-mount .placeholder-37qJjk {
    text-transform: uppercase;
    font-weight: bold;
    letter-spacing: 1.5px;
    font-size: 12px;
    opacity: 0.7;
    left: 15px;
    padding: 0;
  }
  #app-mount .slateTextArea-1Mkdgw {
    left: 0;
    top: 0;
    padding: 15px;
    box-sizing: border-box;
  }
  #app-mount .bd-search-wrapper {
    background: var(--settings-box);
    box-shadow: var(--box-shadow);
  }
  #app-mount .bd-card {
    background-color: var(--settings-box);
    border: none;
    box-shadow: var(--box-shadow);
    padding: 10px;
    box-sizing: border-box;
  }
  #app-mount .bda-header {
    padding: 0 0 10px;
    margin-bottom: 0;
  }
  #app-mount .bda-description {
    margin: 0;
    padding: 10px 0;
  }
  #app-mount .bda-links {
    font-size: 0;
    padding: 10px 0 6px;
  }
  #app-mount .bda-link {
    font-size: 12px;
    background: red;
    background: var(--settings-box-footer);
    border-radius: 15px;
    padding: 4px 10px;
    margin-right: 5px;
    text-decoration: none;
    transition: 0.1s ease;
  }
  #app-mount .bda-link:hover {
    background: rgba(var(--accent), 1);
    color: #fff;
  }
  #app-mount .wrapper-1Rf91z .scroller-2TZvBN {
    background: var(--background-2);
  }
  #app-mount .wrapper-1Rf91z .scroller-2TZvBN::-webkit-scrollbar {
    display: none;
  }
  #app-mount .wrapper-1Rf91z .expandedFolderBackground-2sPsd-, #app-mount .wrapper-1Rf91z .folder-21wGz3 {
    background-color: var(--server-folders);
  }
  #app-mount .wrapper-1Rf91z .wrapper-1BJsBx:hover .childWrapper-anI2G9, #app-mount .wrapper-1Rf91z .wrapper-1BJsBx:hover .circleIconButton-jET_ig {
    color: var(--text-1);
    background: var(--server-hovered);
  }
  #app-mount .wrapper-1Rf91z .childWrapper-anI2G9, #app-mount .wrapper-1Rf91z .circleIconButton-jET_ig {
    background: var(--server-background);
    transition: 0.2s ease;
  }
  #app-mount .wrapper-1Rf91z .childWrapper-anI2G9.selected-ugP_am, #app-mount .wrapper-1Rf91z .circleIconButton-jET_ig.selected-ugP_am {
    color: var(--text-1);
    background: var(--server-selected);
  }
  #app-mount .wrapper-1Rf91z .listItem-2P_4kh.bd-selected .childWrapper-anI2G9, #app-mount .wrapper-1Rf91z .listItem-2P_4kh .selected-bZ3Lue .childWrapper-anI2G9 {
    background: var(--server-selected);
    color: var(--text-1);
  }
  #app-mount .wrapper-1Rf91z .guildsError-b7zR5H {
    background: var(--redDark);
    border-color: var(--redDark);
    color: #fff;
    transition: 0.2s ease;
  }
  #app-mount .wrapper-1Rf91z .guildsError-b7zR5H:hover {
    background: var(--red);
    border-color: var(--red);
  }
  #app-mount .sidebar-2K8pFh {
    background-color: var(--background-1);
  }
  #app-mount .sidebar-2K8pFh .header-2o-2hj {
    box-shadow: none;
    background: transparent !important;
  }
  #app-mount .sidebar-2K8pFh .container-PNkimc {
    background: transparent;
  }
  #app-mount .sidebar-2K8pFh .unread-1xRYoj {
    background-color: var(--channel-selected-bg);
    opacity: 1;
    box-shadow: var(--box-shadow);
  }
  #app-mount .sidebar-2K8pFh .unread-1xRYoj .text-2e2ZyG {
    color: var(--text-1);
  }
  #app-mount .wrapper-CU3qI5 {
    color: var(--text-1);
  }
  #app-mount .wrapper-CU3qI5 .container-2ax-kl {
    color: var(--text-1);
  }
  #app-mount .wrapper-CU3qI5.muted-1NRuDm {
    color: var(--text-dark);
  }
  #app-mount .wrapper-CU3qI5.muted-1NRuDm .container-2ax-kl {
    color: var(--text-dark);
  }
  #app-mount .wrapper-CU3qI5:hover {
    color: var(--text-1);
  }
  #app-mount .wrapper-CU3qI5:hover .container-2ax-kl {
    color: var(--text-1);
  }
  #app-mount .unread-3zKkbm {
    background-color: rgba(var(--accent), 1);
    z-index: 1;
  }
  #app-mount .wrapper-1ucjTd .content-3at_AU {
    margin-left: 0;
    padding-left: 16px;
    border-radius: 0 5px 5px 0;
  }
  #app-mount .wrapper-1ucjTd .content-3at_AU .icon-1_QxNX, #app-mount .wrapper-1ucjTd .content-3at_AU .name-3_Dsmg {
    color: var(--text-3);
  }
  #app-mount .wrapper-1ucjTd.modeMuted-3osy7j .content-3at_AU .icon-1_QxNX, #app-mount .wrapper-1ucjTd.modeMuted-3osy7j .content-3at_AU .name-3_Dsmg {
    color: var(--channel-muted-text);
  }
  #app-mount .wrapper-1ucjTd.modeUnread-1zpFdA .content-3at_AU {
    background: var(--channel-unread-bg);
  }
  #app-mount .wrapper-1ucjTd.modeUnread-1zpFdA .content-3at_AU .icon-1_QxNX, #app-mount .wrapper-1ucjTd.modeUnread-1zpFdA .content-3at_AU .name-3_Dsmg {
    color: var(--channel-unread-text);
  }
  #app-mount .wrapper-1ucjTd:hover .content-3at_AU {
    background: var(--channel-hovered-bg);
  }
  #app-mount .wrapper-1ucjTd:hover .content-3at_AU .icon-1_QxNX, #app-mount .wrapper-1ucjTd:hover .content-3at_AU .name-3_Dsmg {
    color: var(--channel-hovered-text);
  }
  #app-mount .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU {
    box-shadow: inset 4px 0 0 rgba(var(--accent), 1);
    background: var(--channel-selected-bg);
  }
  #app-mount .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU .icon-1_QxNX, #app-mount .wrapper-1ucjTd.modeSelected-1zApJ_ .content-3at_AU .name-3_Dsmg {
    color: var(--channel-selected-text);
  }
  #app-mount .privateChannels-1nO12o {
    background: transparent;
  }
  #app-mount .privateChannels-1nO12o .scroller-1JbKMe {
    background: transparent;
  }
  #app-mount .privateChannels-1nO12o .scroller-1JbKMe div[style="width: 100%; height: 8px; visibility: hidden;"] {
    display: none;
  }
  #app-mount .privateChannels-1nO12o .container-2ax-kl {
    color: var(--text-1);
  }
  #app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 {
    box-shadow: none;
    padding: 0;
    height: auto;
    width: 232px;
    box-sizing: border-box;
  }
  #app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarComponent-32dTOx {
    height: 44px;
    background: transparent;
    border-radius: 0 5px 5px 0;
    font-size: 0;
    display: flex;
    align-items: center;
    padding-left: 16px;
  }
  #app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarComponent-32dTOx:before {
    content: "";
    width: 32px;
    height: 32px;
    display: block;
    -webkit-mask: url('data:image/svg+xml; utf-8, <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M15.5 14h-.79l-.28-.27C15.41 12.59 16 11.11 16 9.5 16 5.91 13.09 3 9.5 3S3 5.91 3 9.5 5.91 16 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19l-4.99-5zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5 14 7.01 14 9.5 11.99 14 9.5 14z"/><path d="M0 0h24v24H0z" fill="none"/></svg>') center/24px no-repeat;
    background: var(--text-3);
    margin-right: 12px;
    position: relative;
    z-index: 1;
    pointer-events: none;
  }
  #app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarComponent-32dTOx:after {
    content: "Search";
    font-size: 16px;
    line-height: 20px;
    font-weight: 500;
    color: var(--text-3);
    position: relative;
    z-index: 1;
    pointer-events: none;
  }
  #app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarComponent-32dTOx:hover {
    background: var(--channel-hovered-bg);
  }
  #app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarComponent-32dTOx:hover:before {
    background: var(--text-2);
  }
  #app-mount .privateChannels-1nO12o .searchBar-6Kv8R2 .searchBarComponent-32dTOx:hover:after {
    color: var(--text-2);
  }
  #app-mount .privateChannels-1nO12o .channel-2QD9_O {
    margin: 0;
    max-width: 100%;
    color: var(--text-3);
  }
  #app-mount .privateChannels-1nO12o .channel-2QD9_O .layout-2DM8Md {
    padding-left: 16px;
    border-radius: 0 5px 5px 0;
  }
  #app-mount .privateChannels-1nO12o .channel-2QD9_O:hover {
    color: var(--text-2);
  }
  #app-mount .privateChannels-1nO12o .channel-2QD9_O:hover .layout-2DM8Md {
    background: var(--channel-hovered-bg);
  }
  #app-mount .privateChannels-1nO12o .channel-2QD9_O.selected-aXhQR6 {
    color: var(--text-1);
  }
  #app-mount .privateChannels-1nO12o .channel-2QD9_O.selected-aXhQR6 .layout-2DM8Md {
    background: var(--channel-selected-bg);
    box-shadow: inset 4px 0 0 rgba(var(--accent), 1);
  }
  #app-mount .panels-j1Uci_ {
    background-color: var(--background-1);
  }
  #app-mount .panels-j1Uci_ .container-1giJp5 {
    border: none;
  }
  #app-mount .panels-j1Uci_ .button-14-BFJ.enabled-2cQ-u7:hover {
    color: var(--text-1);
    background-color: var(--foreground-1);
  }
  #app-mount .wrapper-3WhCwL {
    color: rgba(var(--accent), 1);
    background: rgba(var(--accent), 0.1);
  }
  #app-mount .wrapper-3WhCwL:hover {
    background: rgba(var(--accent), 1);
    color: #fff;
  }
