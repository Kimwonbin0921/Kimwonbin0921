<svg xmlns="http://www.w3.org/2000/svg" width="480" height="199" class="">
    <defs>
        <style/>
    </defs>
    <style>/* SVG global context */
  svg {
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
    font-size: 14px;
    color: #777777;
  }

/* Large SVG context */
  svg.large .largeable {
    width: 474px;
  }
  svg.large .largeable &gt; .row {
    width: 100%;
  }
  svg.large .largeable-align-start {
    align-items: flex-start;
  }
  svg.large .column.largeable, svg.large .row.largeable, svg.large .largeable-inline-flex {
    display: inline-flex;
  }
  svg.large .largeable-flex-wrap, svg.large .largeable-column-fields {
    display: flex;
    flex-wrap: wrap;
  }
  svg.large .largeable-column-fields &gt; .field {
    width: 230px;
  }
  svg.large .chart.largeable {
    width: 458px;
  }
  svg.large .largeable-width-auto {
    width: auto;
  }
  svg.large .largeable-width-half {
    width: 50%;
  }

/* Columns display */
  svg.columns .items-wrapper{
    column-count: 2;
    column-gap: 10px;
  }
  svg.columns .items-wrapper&gt;*{
    -webkit-column-break-inside: avoid;
    page-break-inside: avoid;
    break-inside: avoid-column;
  }

  @media (max-width: 850px){
    svg.columns .items-wrapper{
      column-count: 1;
    }
  }

/* Headers */
  h1, h2, h3 {
    margin: 8px 0 2px;
    padding: 0;
    color: #0366d6;
    font-weight: normal;
  }
  h1 svg, h2 svg, h3 svg {
    fill: currentColor;
  }
  h1 {
    font-size: 20px;
    font-weight: bold;
  }
  h2 {
    font-size: 16px;
  }
  h3 {
    font-size: 14px;
  }
  .h-details {
    margin: 0 4px;
    padding-top: 4px;
    font-size: 0.8rem;
  }

/* Fields */
  section &gt; .field {
    margin-left: 5px;
    margin-right: 5px;
  }
  .field {
    display: flex;
    align-items: center;
    margin-bottom: 2px;
    white-space: nowrap;
  }
  .field.wrap {
    flex-wrap: wrap;
  }
  .field svg {
    margin: 0 8px;
    fill: #959da5;
    flex-shrink: 0;
  }
  .field.error {
    color: #cb2431;
  }
  .field.error svg {
    fill: #cb2431;
  }

/* Displays */
  .row {
    display: flex;
    flex-wrap: wrap;
  }
  .row section {
    flex: 1 1 0;
  }
  .column {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .center {
    justify-content: center;
  }
  .horizontal {
    justify-content: space-around;
  }
  .horizontal-wrap {
    flex-wrap: wrap;
  }
  .horizontal .field {
    flex: 1 1 0;
  }
  .no-wrap {
    white-space: nowrap;
  }
  .fill-width {
    width: 100%;
  }
  .margin-bottom {
    margin-bottom: 16px;
  }
  .no-margin-top {
    margin-top: 0px;
  }

/* User avatar */
  .avatar {
    border-radius: 50%;
    margin: 0 6px;
  }

  .organization.avatar {
    border-radius: 15%;
  }

  .organization.name {
    white-space: nowrap;
  }

  .organization.contributions {
    margin: 0 8px;
    flex-wrap: wrap;
  }

  .contribution.organization {
    display: flex;
    border: 1px solid #959da5;
    border-radius: 6px;
    padding: 2px 6px;
    padding-left: 0;
    margin: 2px;
    font-size: 12px;
    background-color: #959da520;
  }

  .contribution.organization .avatar {
    margin: 0 4px;
  }

/* Commit calendar */
  .calendar.field {
    margin: 4px 0;
    margin-left: 7px;
  }
  .calendar .day {
    outline: 1px solid rgba(27,31,35,.04);
    outline-offset: -1px;
  }

/* Progress bars */
  svg.bar {
    margin: 4px 0;
  }

/* Language */
  .field.language {
    margin: 0 8px;
    flex-grow: 0;
  }

  .field.language.details {
    display: flex;
    justify-content: space-between;
  }

  .field.language.details small {
    display: flex;
    justify-content: space-between;
    color: #666666;
    text-align: right;
  }

  .field.language.details &gt; *, .field.language.details small &gt; * {
    flex: 1 1 0;
  }
  .field.language.details small &gt; *:not(:last-child) {
    margin-right: 6px;
  }

/* Follow-up */
  .followup.legend {
    font-size: 12px;
  }
  .followup.legend svg {
    margin: 0 3px;
    width: 14px;
    height: 14px;
  }
  .followup.legend svg:first-child {
    margin-left: 0;
  }
  .followup.legend svg:last-child {
    margin-right: 0;
  }
  .followup-title{
    white-space: initial;
  }

/* Labels */
  .label {
    background-color: #58A6FF30;
    color: #0366D6;
    padding: 0 10px;
    font-weight: 500;
    line-height: 22px;
    margin: 2px 5px;
    white-space: nowrap;
    border-radius: 32px;
    font-size: 12px;
  }
  .label.label-flex {
    display: flex;
  }
  .label .label-right {
    display: flex;
    align-items: center;
    font-size: .7rem;
    margin-left: 6px;
    margin-right: -10px;
    background-color: #58A6FF10;
    padding: 0 7px;
    border-top-right-radius: 32px;
    border-bottom-right-radius: 32px;
  }
  .label .twemoji {
    margin-top: .25em;
    margin-left: 0px;
  }

/* Habits */
  .habits {
    margin: 0;
    list-style-type: none;
    padding-left: 37px;
  }

/* Footer */
  footer {
    margin-top: 8px;
    font-size: 10px;
    font-style: italic;
    color: #666666;
    text-align: right;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    padding: 0 4px;
  }

/* Speed test categories */
  .categories {
    display: flex;
    align-items: center;
    justify-content: space-around;
    margin-top: 4px;
  }
  .category {
    display: flex;
    flex-direction: column;
    align-items: center;
    flex: 1 1 0;
  }

/* Gauges */
  .gauge {
    stroke-linecap: round;
    fill: none;
  }
  .gauge.high {
    color: #18b663;
  }
  .gauge.average {
    color: #fb8c00;
  }
  .gauge.low {
    color: #e53935;
  }
  .gauge.info {
    color: #58A6FF;
  }
  .gauge-base, .gauge-arc {
    stroke: currentColor;
    stroke-width: 10;
  }
  .gauge-base {
    stroke-opacity: .2;
  }
  .gauge-arc {
    fill: none;
    stroke-dashoffset: 0;
    animation-delay: 250ms;
    animation: animation-gauge 1s ease forwards
  }
  .gauge text {
    fill: currentColor;
    font-size: 40px;
    font-family: monospace;
    text-anchor: middle;
    font-weight: 600;
  }
  .gauge .title {
    font-size: 18px;
    color: #777777;
  }
  @keyframes animation-gauge {
    from {
      stroke-dasharray: 0 329;
    }
  }
  .audits {
    margin-top: 8px;
  }
  .audit.text {
    min-width: 42px;
  }
  .audit svg {
    margin: 0;
  }
  .audit.high {
    fill: #18b663;
  }
  .audit.average {
    fill: #fb8c00;
  }
  .audit.low {
    fill: #e53935;
  }

  .screenshot {
    width: 452px;
    height: 315px;
    margin: 8px 14px 4px;
    border-radius: 5px;
  }

  svg.large .audits {
    display: inline-flex;
    width: 474px;
  }
  svg.large .audits section:last-child &gt; .field {
    justify-content: right;
  }
  svg.large .screenshot {
    width: 904px;
    height: 630px;
  }

/* Music plugin */
  .tracklist {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-left: 28px;
    margin-top: 4px;
    width: 100%;
  }
  .track {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 4px;
  }
  .track img {
    margin: 0 10px;
    border-radius: 7px;
    flex-shrink: 0;
  }
  .track .name {
    font-size: 14px;
    line-height: 14px;
    font-weight: 600;
  }
  .track .artist, .track .played-at {
    font-size: 12px;
    color: #666666;
  }
  .track .infos {
    flex-grow: 1;
  }
  svg.large .tracklist {
    flex-direction: row;
    flex-wrap: wrap;
  }
  svg.large .track {
    width: 25%;
  }

/* Posts plugin */
  .post {
    align-items: flex-start;
  }
  .post .infos {
    display: flex;
    margin-bottom: 4px;
  }
  .post .infos .left {
    flex-shrink: 0;
    font-size: 12px;
    color: #666666;
    width: 72px;
    padding-top: 1px;
    text-align: center;
  }
  .post .infos .cover {
    width: 100%;
    height: 56px;
    background-position: center;
    background-size: cover;
    border-radius: 6px;
    overflow: hidden;
  }
  .post .infos .right {
    width: 376px;
    padding-left: 4px;
  }
  .post .infos .title, .post .infos .description {
    font-size: 14px;
    white-space: normal;
    overflow: hidden;
    text-overflow: ellipsis;
    max-height: 38px;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }
  .post .infos .description {
    margin-top: 3px;
    font-size: 12px;
    max-height: 48px;
    color: #666666;
    -webkit-line-clamp: 3;
  }

/* Topics */
  .topics {
    display: flex;
    flex-wrap: wrap;
  }

  .topics img {
    border-radius: 5px;
    margin: 4px;
  }

/* Tweets */
  .tweet {
    font-size: 13px;
    margin-top: 6px;
    margin-bottom: 16px;
    margin-left: 18px;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
  }

  .tweet .mention, .tweet .link, .tweet .hashtag {
    color: #0366d6;
  }

  .tweet .date {
    margin: 6px 0;
    font-size: 12px;
    color: #666666;
  }

  .tweet .attachments {
    display: flex;
    width: 450px;
    margin-top: 8px;
  }

  .tweet .attachments &gt; div {
    flex: 1 1 0;
    width: 0;
    border-radius: 6px;
    background-position: center;
    background-size: cover;
    height: 200px;
    margin: 2px;
    box-shadow: 0px 0px 1px #777777A0;
    overflow: hidden;
    display: flex;
    align-items: flex-end;
  }

  .tweet .attachments .infos {
    background-color: #000000D0;
    color: white;
    display: flex;
    flex-direction: column;
    width: 100%;
    padding-bottom: 4px;
  }

  .tweet .attachments .infos &gt; div {
    margin: 4px 8px 0;
  }

  .tweet .attachments .infos .title {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  .tweet .attachments .infos .description {
    font-size: 11px;
    color: #666666;
  }

/* Charts and graphs */
  .chart {
    padding: 0 8px;
  }

  .chart-bars {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    width: 100%;
    margin: 8px 0 4px;
    flex-grow: 1;
    min-height: 70px;
  }

  .chart-bars .entry {
    flex: 1 1 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 10px;
    color: #666666;
  }

  .chart-bars .entry .value {
    font-size: 7px;
  }

  .chart-bars .entry .empty {
    width: 100%;
    text-align: center;
  }

  .chart-bars .bar {
    width: 7px;
    background-color: var(--color-calendar-graph-day-bg);
    border: 1px solid var(--color-calendar-graph-day-border);
    border-radius: 5px;
  }

  .chart-bars.horizontal {
    flex-direction: column;
    height: 100%;
  }

  .chart-bars.horizontal .entry {
    align-items: center;
    flex-direction: row;
    width: 100%;
    min-height: 1rem;
  }

  .chart-bars.horizontal .entry .name {
    flex-shrink: 0;
    text-align: right;
    width: 34%;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }

  .chart-bars .entry .bottom {
    margin-bottom: -1rem;
    line-height: 1rem;
  }

  .chart-bars.horizontal .bar {
    height: 7px;
    width: auto;
    margin: 0 6px;
  }

/* Repository */
  .repository {
    display: flex;
    flex-direction: column;
    width: 100%;
    margin: 6px 0;
  }

  .repository .name {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 440px;
  }

  .repository .name span:first-child {
    color: #58a6ff;
  }

  .repository .name span:last-child {
    color: #666666;
    font-size: 10px;
  }

  .repository .description {
    display: block;
    width: 440px;
    white-space: normal;
  }

  .repository .description, .repository .infos {
    color: #666666;
    margin-left: 38px;
    font-size: 13px;
  }

  .repository .infos &gt; div {
    display: flex;
    align-items: center;
    margin-right: 16px;
  }

  .repository .infos svg {
    margin: 0;
    margin-right: 4px;
  }

/* Activity */
  .activity {
    margin-bottom: 12px;
  }

  .activity .field {
    width: 100%;
    overflow: hidden;
    text-overflow: ellipsis;
    max-width: 450px;
    white-space: nowrap;
    margin-bottom: 0;
  }

  .activity .field .content {
    flex-grow: 1;
    text-overflow: ellipsis;
    overflow: hidden;
  }

  .activity .repo, .activity .issue, .activity .commit .sha {
    display: inline;
    color: #58a6ff;
  }

  .activity .code {
    background-color: #7777771F;
    padding: 1px 5px;
    font-size: 80%;
    border-radius: 6px;
    color: #777777;
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
    margin: 0 4px -3px;
  }

  .activity .bold, .activity .user {
    font-weight: 600;
  }

  .activity .details, .activity .timestamp {
    padding-left: 38px;
    display: flex;
    flex-direction: column;
    font-size: 13px;
    color: #666666;
  }

  .activity .timestamp {
    font-size: 10px;
    margin-top: 4px;
  }

  .activity .commit .sha {
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
  }

  .activity .commit .message {
    overflow: hidden;
    text-overflow: ellipsis;
    width: 360px;
    white-space: nowrap;
  }

  .activity .details &gt; .comment {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 420px;
    margin-top: 6px;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

  svg.large .activity .field {
    max-width: 900px;
  }

/* People */
  .people {
    padding: 0 10px;
  }

  .people .avatar {
    margin: 0 2px;
  }

/* Projects */
  .project .description {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 420px;
    margin-left: 37px;
    max-height: 38px;
    font-size: 12px;
    white-space: normal;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

/* Anilist */
  .anilist {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-left: 28px;
    margin-top: 4px;
  }

  .anilist .media {
    display: flex;
    margin-bottom: 4px;
    width: 450px;
  }
  .anilist .media img {
    margin: 0 10px;
    border-radius: 7px;
  }

  .anilist .media .about {
    flex-grow: 1;
  }
  .anilist .media .name {
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 14px;
    line-height: 14px;
    color: #58a6ff;
  }
  .anilist .media .infos {
    font-size: 12px;
    color: #666666;
  }
  .anilist .media .infos &gt; div {
    display: inline-flex;
    align-items: center;
    margin-right: 16px;
  }
  .anilist .media .infos svg {
    fill: currentColor;
    height: 12px;
    width: 12px;
    margin: 0;
    margin-right: 4px;
  }

  .anilist .media .description {
    overflow: hidden;
    text-overflow: ellipsis;
    display: block;
    width: 380px;
    max-height: 38px;
    font-size: 12px;
    white-space: normal;
    /* May not work in all browsers */
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
  }

  .anilist .characters {
    display: flex;
    flex-wrap: wrap;
  }

  .anilist .characters img {
    margin: 2px;
    border-radius: 7px;
  }

/* Licenses */
  .licenses {
    display: flex;
  }
  .licenses .column {
    align-items: flex-start;
    font-size: 12px;
    color: #666666;
    flex-shrink: 0;
  }
  .licenses-details {
    margin-top: 8px;
  }
  .field.license.details {
    display: flex;
    justify-content: space-between;
  }
  .field.license.details small {
    display: flex;
    justify-content: space-between;
    color: #666666;
    text-align: right;
  }
  .licenses .column:nth-child(1) {
    margin-left: 13px;
    width: 25%;
  }
  .licenses .column:nth-child(2) {
    width: 25%;
  }
  .licenses .column:nth-child(3) {
    width: 50%;
  }
  .licenses .column svg {
    height: 12px;
    width: 12px;
  }
  .licenses .column .title {
    font-weight: 600;
    margin-left: 15px;
  }
  .licenses .column .permission svg {
    fill: #56d364;
  }
  .licenses .column .limitation svg {
    fill: #f85149;
  }
  .licenses .column .condition svg {
    fill: #58a6ff;
  }

/* Contributors */
  .contributors {
    display: flex;
    flex-wrap: wrap;
    margin-left: 6px;
  }
  .contributors .label {
    padding-left: 0;
    display: flex;
    align-items: center;
  }
  .contributors .label img {
    margin-left: 0;
  }
  .contributors .contributions {
    display: flex;
    align-items: center;
    font-size: .7rem;
    margin-left: 6px;
    margin-right: -10px;
    background-color: #58A6FF10;
    padding: 0 7px;
    border-top-right-radius: 32px;
    border-bottom-right-radius: 32px;
  }
  .contributors .contributions svg {
    fill: #0366D6;
    margin-left: 4px;
    width: .8rem;
    height: .8rem;
  }
  .field.contributors-category {
    margin-left: 12px;
  }
  .contributors-categories img {
    margin-right: 0;
  }

/* Introduction and sponsors */
  .introduction, .sponsors {
    white-space: normal;
    margin: 0 13px 2px;
  }
  .sponsors.goal {
    padding: 6px 8px;
    border-radius: 5px;
    background-color: #7777771F;
  }
  .sponsors .goal-text {
    display: flex;
    justify-content: space-between;
    font-style: italic;
    font-size: 10px;
    margin-bottom: 4px;
  }
  .sponsors .avatar {
    margin: 2px;
  }

/* Stackoverflow */
  .stackoverflow {
    margin-left: 38px;
  }
  .stackoverflow .entry {
    margin: 4px 0 12px;
  }
  .stackoverflow .title {
    color: #58a6ff;
    white-space: normal;
    align-items: flex-start;
  }
  .stackoverflow .body, .stackoverflow .infos {
    color: #666666;
    font-size: 13px;
    margin-left: 32px;
  }
  .stackoverflow .infos {
    display: flex;
    align-items: center;
  }
  .stackoverflow .infos &gt; div {
    display: inline-flex;
    align-items: center;
    margin-right: 16px;
  }
  .stackoverflow .infos svg {
    fill: currentColor;
    height: 12px;
    width: 12px;
    margin: 0;
    margin-right: 4px;
    flex-shrink: 0;
  }
  .stackoverflow .body {
    overflow: hidden;
    text-overflow: ellipsis;
    border-left: 3px solid #777777B2;
    padding-left: 6px;
    width: 400px;
  }

/* Achievements */
  .achievement {
    display: flex;
    margin: 4px 0;
  }
  .achievement .icon {
    margin: 0 4px;
    width: 44px;
    height: 44px;
  }
  .achievement .text {
    font-size: 12px;
    color: #666666;
  }
  .achievement .unlock {
    font-size: 9px;
    color: #666666;
  }
  .achievement .title {
    font-size: 14px;
    color: #58A6FF;
  }
  .achievement .gauge.info {
    color: #58A6FF;
  }
  .achievement .value {
    background-color: #58A6FF26;
  }
  .achievement.x .title {
    color: #666666;
  }
  .achievement.x .gauge.info {
    color: #B0B0B0;
  }
  .achievement.x .value {
    background-color: #B0B0B026;
  }
  .achievement.b .title {
    color: #9D8FFF;
  }
  .achievement.b .gauge.info {
    color: #9E91FF;
  }
  .achievement.b .value {
    background-color: #9E91FF26;
  }
  .achievement.a .title {
    color: #D79533;
  }
  .achievement.a .gauge.info {
    color: #E7BD69;
  }
  .achievement.a .value {
    background-color: #E7BD6926;
  }
  .achievement.s .title {
    color: #EB355E;
  }
  .achievement.s .gauge.info {
    color: #EB355E;
  }
  .achievement.s .value {
    background-color: #EB355E26;
  }
  .achievement.secret .title{
    color: #FF76CD;
  }
  .achievement.secret .gauge.info {
    color: #FF79D1;
  }
  .achievement.secret .value {
    background-color: #FF79D126;
  }
  .achievement .gh, .achievement .value {
    border: 1px solid currentColor;
    border-radius: 16px;
    font-size: 10px;
    padding: 0 5px;
    white-space: nowrap;
  }
  .achievement .gauge-base, .achievement .gauge-arc {
    stroke-width: 6;
  }
  .achievement .value-wrapper {
    margin-bottom: -50px;
    margin-top: 36px;
    display: none;
    position: relative;
  }
  .achievement .value {
    margin-left: 46px;
  }
  .achievements.compact {
    display: flex;
    flex-wrap: wrap;
  }
  .achievements.compact .achievement {
    flex-direction: column-reverse;
    align-items: center;
    width: 80px;
  }
  .achievements.compact .info {
    width: 100%;
  }
  .achievements.compact .achievement .title {
    margin-bottom: 2px;
    text-transform: capitalize;
    text-align: center;
  }
  .achievements.compact .achievement .title .prefix {
    min-height: 13px;
    font-size: 10px;
    display: block;
    margin-bottom: -.25rem;
  }
  .achievements.compact .achievement .value-wrapper {
    display: flex;
  }
  .achievements.compact .achievement .text, .achievements.compact .achievement .gh {
    display: none;
  }

/* RSS feed */
  .rss {
    align-items: flex-start;
  }
  .rss .infos {
    margin-bottom: 3px;
  }
  .rss .infos .date {
    font-size: 10px;
    color: #666666;
  }

/* Skyline */
  .skyline-animation {
    margin: 2px 13px 6px;
    border-radius: 10px;
    background-color: #030D21;
    overflow: hidden;
  }

/* Code snippet */
  .snippet .body {
    padding-left: 12px;
  }
  .snippet.additions {
    color: #336543;
  }
  .snippet.deletions {
    color: #9A5256;
  }

/* Markdown and syntax highlighting */
  .markdown b, .markdown i {
    display: inline-block;
    width: 97%;
  }
  .markdown p {
    margin: 8px 0;
  }
  .markdown ul {
    padding-left: 24px;
  }
  .markdown a {
    color: #58a6ff;
    text-decoration: none;
  }
  .markdown blockquote {
    border-left: 4px solid #7777771F;
    color: #777777;
    margin: 0;
    padding-left: 16px;
  }
  code {
    background-color: #7777771F;
    display: inline-block;
    border-radius: 6px;
    color: #777777;
    padding: 1px 5px;
    font-size: 80%;
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
  }
  code[class^=language-] {
    white-space: pre-wrap;
    width: 97%;
    margin-top: 4px;
  }
  span.code {
    background-color: #7777771F;
    padding: 1px 5px;
    font-size: 80%;
    border-radius: 6px;
    color: #777777;
    font-family: SFMono-Regular,Consolas,Liberation Mono,Menlo,monospace;
    margin: 0 4px -3px;
  }
  .token.comment {
    color: #669900;
  }
  .token.punctuation {
    color: #8a93a8;
  }
  .token.namespace, .token.constant, .token.symbol, .token.keyword {
    color: #b44418;
  }
  .token.regex, .token.string, .token.char, .token.number, .token.boolean {
    color: #2777AA;
  }
  .token.property, .token.tag {
    color: #48428a;
  }
  .token.builtin, .token.operator {
    color: #106cbc;
  }
  .token.trimmed {
    font-style: italic;
    color: #77777760;
  }
  .token.coord {
    color: #D2A8FF;
    font-weight: bold;
  }
  .token.inserted:not(.prefix) {
    color: #AAD0B4DC;
    background-color: #336543DC;
  }
  .token.deleted:not(.prefix) {
    color: #EED2D0DC;
    background-color: #9A5256DC;
  }

/* Typography */
  .space {
    margin-left: 7px;
  }
  .blue {
    color: #58a6ff;
  }

/* Charts */
  .ct-line {
    stroke-width: 2px !important;
    stroke: #58A6FF !important;
  }
  .ct-area {
    fill: #58A6FF !important;
  }
  .ct-label {
    fill: rgba(127, 127, 127, 0.8) !important;
    color: rgba(127, 127, 127, 0.8) !important;
  }
  .ct-grid {
    stroke: rgba(127, 127, 127, 0.4) !important;
  }

/* Autosize */
  .autosize {
    width: auto;
    height: auto;
  }

/* Fade animation */
  .af {
    opacity: 0;
    animation: animation-fade 1s ease forwards;
  }
  @keyframes animation-fade {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

/* Twemoji and GitHub emoji */
  .twemoji, .gemoji {
    height: 1em;
    width: 1em;
    margin-bottom: -.125em;
  }

/* Cake day */
  .cakeday, .cakeday svg {
    animation: animation-rainbow 1.2s;
    animation-iteration-count: infinite;
    animation-timing-function: steps(1);
  }

/* Rainbow animation */
  @keyframes animation-rainbow {
    0%, 100%{ color: #7F00FF; fill: #7F00FF; }
    14% { color: #A933FF; fill: #A933FF; }
    29%{ color: #007FFF; fill: #007FFF; }
    43%{ color: #00FF7F; fill: #00FF7F; }
		57%{ color: #FFFF00; fill: #FFFF00; }
		71%{ color: #FF7F00; fill: #FF7F00; }
		86%{ color: #FF0000; fill: #FF0000; }
  }

/* Calendar */
  :root {
    --color-calendar-graph-day-bg: #ebedf0;
    --color-calendar-graph-day-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L1-bg: #9be9a8;
    --color-calendar-graph-day-L2-bg: #40c463;
    --color-calendar-graph-day-L3-bg: #30a14e;
    --color-calendar-graph-day-L4-bg: #216e39;
    --color-calendar-halloween-graph-day-L1-bg: #ffee4a;
    --color-calendar-halloween-graph-day-L2-bg: #ffc501;
    --color-calendar-halloween-graph-day-L3-bg: #fe9600;
    --color-calendar-halloween-graph-day-L4-bg: #03001c;
    --color-calendar-graph-day-L4-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L3-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L2-border: rgba(27,31,35,0.06);
    --color-calendar-graph-day-L1-border: rgba(27,31,35,0.06);
  }

/* End delimiter */
  #metrics-end {
    width: 100%;
  }

  .no-animations * {
    transition-delay: 0s !important;
    transition-duration: 0s !important;
    animation-delay: -0.0001s !important;
    animation-duration: 0s !important;
    animation-play-state: paused !important;
    caret-color: transparent !important;
  }</style>
    <foreignObject x="0" y="0" width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml" xmlns:xlink="http://www.w3.org/1999/xlink" class="items-wrapper">
            <section>
                <h2 class="field">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M4.75 0a.75.75 0 01.75.75V2h5V.75a.75.75 0 011.5 0V2h1.25c.966 0 1.75.784 1.75 1.75v10.5A1.75 1.75 0 0113.25 16H2.75A1.75 1.75 0 011 14.25V3.75C1 2.784 1.784 2 2.75 2H4V.75A.75.75 0 014.75 0zm0 3.5h8.5a.25.25 0 01.25.25V6h-11V3.75a.25.25 0 01.25-.25h2zm-2.25 4v6.75c0 .138.112.25.25.25h10.5a.25.25 0 00.25-.25V7.5h-11z"/></svg>
      Contributions calendar
    </h2>
                <div class="row">
                    <section>
                    </section>
                    <section>
                        <h3 class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M7.75 14A1.75 1.75 0 016 12.25v-8.5C6 2.784 6.784 2 7.75 2h6.5c.966 0 1.75.784 1.75 1.75v8.5A1.75 1.75 0 0114.25 14h-6.5zm-.25-1.75c0 .138.112.25.25.25h6.5a.25.25 0 00.25-.25v-8.5a.25.25 0 00-.25-.25h-6.5a.25.25 0 00-.25.25v8.5zM4.9 3.508a.75.75 0 01-.274 1.025.25.25 0 00-.126.217v6.5a.25.25 0 00.126.217.75.75 0 01-.752 1.298A1.75 1.75 0 013 11.25v-6.5c0-.649.353-1.214.874-1.516a.75.75 0 011.025.274zM1.625 5.533a.75.75 0 10-.752-1.299A1.75 1.75 0 000 5.75v4.5c0 .649.353 1.214.874 1.515a.75.75 0 10.752-1.298.25.25 0 01-.126-.217v-4.5a.25.25 0 01.126-.217z"/></svg>
            Commits streaks
          </h3>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path d="M8.5.75a.75.75 0 00-1.5 0v5.19L4.391 3.33a.75.75 0 10-1.06 1.061L5.939 7H.75a.75.75 0 000 1.5h5.19l-2.61 2.609a.75.75 0 101.061 1.06L7 9.561v5.189a.75.75 0 001.5 0V9.56l2.609 2.61a.75.75 0 101.06-1.061L9.561 8.5h5.189a.75.75 0 000-1.5H9.56l2.61-2.609a.75.75 0 00-1.061-1.06L8.5 5.939V.75z"/></svg>
            Best streak 31 days
          </div>
                        <h3 class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path fill-rule="evenodd" d="M10.5 7.75a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0zm1.43.75a4.002 4.002 0 01-7.86 0H.75a.75.75 0 110-1.5h3.32a4.001 4.001 0 017.86 0h3.32a.75.75 0 110 1.5h-3.32z"/></svg>
            Commits per day
          </h3>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path d="M7.823 1.677L4.927 4.573A.25.25 0 005.104 5H7.25v3.236a.75.75 0 101.5 0V5h2.146a.25.25 0 00.177-.427L8.177 1.677a.25.25 0 00-.354 0zM13.75 11a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zm-3.75.75a.75.75 0 01.75-.75h.5a.75.75 0 010 1.5h-.5a.75.75 0 01-.75-.75zM7.75 11a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5zM4 11.75a.75.75 0 01.75-.75h.5a.75.75 0 010 1.5h-.5a.75.75 0 01-.75-.75zM1.75 11a.75.75 0 000 1.5h.5a.75.75 0 000-1.5h-.5z"/></svg>
            Highest in a day at 64
          </div>
                        <div class="field">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16"><path d="M10.896 2H8.75V.75a.75.75 0 00-1.5 0V2H5.104a.25.25 0 00-.177.427l2.896 2.896a.25.25 0 00.354 0l2.896-2.896A.25.25 0 0010.896 2zM8.75 15.25a.75.75 0 01-1.5 0V14H5.104a.25.25 0 01-.177-.427l2.896-2.896a.25.25 0 01.354 0l2.896 2.896a.25.25 0 01-.177.427H8.75v1.25zm-6.5-6.5a.75.75 0 000-1.5h-.5a.75.75 0 000 1.5h.5zM6 8a.75.75 0 01-.75.75h-.5a.75.75 0 010-1.5h.5A.75.75 0 016 8zm2.25.75a.75.75 0 000-1.5h-.5a.75.75 0 000 1.5h.5zM12 8a.75.75 0 01-.75.75h-.5a.75.75 0 010-1.5h.5A.75.75 0 0112 8zm2.25.75a.75.75 0 000-1.5h-.5a.75.75 0 000 1.5h.5z"/></svg>
            Average per day at ~2.54
          </div>
                    </section>
                </div>
                <svg version="1.1" xmlns="http://www.w3.org/2000/svg" style="margin-top: -130px;" viewBox="0,0 480,170">
                    <filter id="brightness1">
                        <feComponentTransfer>
                            <feFuncR type="linear" slope="0.6"/>
                            <feFuncG type="linear" slope="0.6"/>
                            <feFuncB type="linear" slope="0.6"/>
                        </feComponentTransfer>
                    </filter>
                    <filter id="brightness2">
                        <feComponentTransfer>
                            <feFuncR type="linear" slope="0.19999999999999996"/>
                            <feFuncG type="linear" slope="0.19999999999999996"/>
                            <feFuncB type="linear" slope="0.19999999999999996"/>
                        </feComponentTransfer>
                    </filter>
                    <g transform="scale(4) translate(12, 0)">
                        <g transform="translate(0, 0)">
                            <g transform="translate(0, 4.875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.125 0,2.125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.125 1.7,3.125 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.53125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.46875 0,1.46875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.46875 1.7,2.46875 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.6875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.3125 0,2.3125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.3125 1.7,3.3125 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.78125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.21875 0,2.21875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.21875 1.7,3.21875 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.59375)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.40625 0,2.40625 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.40625 1.7,3.40625 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                        </g>
                        <g transform="translate(1.7, 1)">
                            <g transform="translate(0, 4.78125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.21875 0,2.21875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.21875 1.7,3.21875 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.15625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.84375 0,1.84375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.84375 1.7,2.84375 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 8.40625)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.59375 0,2.59375 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.59375 1.7,3.59375 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.25)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.75 0,1.75 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.75 1.7,2.75 z"/>
                            </g>
                        </g>
                        <g transform="translate(3.4, 2)">
                            <g transform="translate(0, 5.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                            <g transform="translate(-1.7, 3.4375)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,5.5625 0,4.5625 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,4.5625 1.7,5.5625 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.34375)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.65625 0,1.65625 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.65625 1.7,2.65625 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.59375)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.40625 0,2.40625 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.40625 1.7,3.40625 z"/>
                            </g>
                            <g transform="translate(-6.8, 8.78125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.21875 0,2.21875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.21875 1.7,3.21875 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.25)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.75 0,1.75 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.75 1.7,2.75 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.0625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9375 0,1.9375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9375 1.7,2.9375 z"/>
                            </g>
                        </g>
                        <g transform="translate(5.1, 3)">
                            <g transform="translate(0, 4.03125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.96875 0,2.96875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.96875 1.7,3.96875 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.0625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9375 0,1.9375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9375 1.7,2.9375 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.875 0,2.875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.875 1.7,3.875 z"/>
                            </g>
                            <g transform="translate(-6.8, 8.96875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.03125 0,2.03125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.03125 1.7,3.03125 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.4375)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5625 0,1.5625 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5625 1.7,2.5625 z"/>
                            </g>
                            <g transform="translate(-10.2, 8.8125)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,5.1875 0,4.1875 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,4.1875 1.7,5.1875 z"/>
                            </g>
                        </g>
                        <g transform="translate(6.8, 4)">
                            <g transform="translate(0, 0)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,8 0,7 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,7 1.7,8 z"/>
                            </g>
                            <g transform="translate(-1.7, 4.9375)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.0625 0,3.0625 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.0625 1.7,4.0625 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.03125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.96875 0,2.96875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.96875 1.7,3.96875 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.0625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9375 0,1.9375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9375 1.7,2.9375 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.53125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.46875 0,1.46875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.46875 1.7,2.46875 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                        </g>
                        <g transform="translate(8.5, 5)">
                            <g transform="translate(0, 5.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.0625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9375 0,1.9375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9375 1.7,2.9375 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.21875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.78125 0,2.78125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.78125 1.7,3.78125 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.78125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.21875 0,2.21875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.21875 1.7,3.21875 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.15625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.84375 0,1.84375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.84375 1.7,2.84375 z"/>
                            </g>
                            <g transform="translate(-8.5, 7.71875)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,5.28125 0,4.28125 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,4.28125 1.7,5.28125 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.15625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.84375 0,1.84375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.84375 1.7,2.84375 z"/>
                            </g>
                        </g>
                        <g transform="translate(10.2, 6)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.875 0,2.875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.875 1.7,3.875 z"/>
                            </g>
                            <g transform="translate(-5.1, 6.75)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.25 0,3.25 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.25 1.7,4.25 z"/>
                            </g>
                            <g transform="translate(-6.8, 7.46875)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.53125 0,3.53125 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.53125 1.7,4.53125 z"/>
                            </g>
                            <g transform="translate(-8.5, 8.75)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.25 0,3.25 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.25 1.7,4.25 z"/>
                            </g>
                            <g transform="translate(-10.2, 9.5625)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.4375 0,3.4375 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.4375 1.7,4.4375 z"/>
                            </g>
                        </g>
                        <g transform="translate(11.9, 7)">
                            <g transform="translate(0, 5.53125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.46875 0,1.46875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.46875 1.7,2.46875 z"/>
                            </g>
                            <g transform="translate(-1.7, 5.875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.125 0,2.125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.125 1.7,3.125 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.3125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.6875 0,2.6875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.6875 1.7,3.6875 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.96875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.03125 0,2.03125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.03125 1.7,3.03125 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.96875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.03125 0,2.03125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.03125 1.7,3.03125 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.34375)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.65625 0,1.65625 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.65625 1.7,2.65625 z"/>
                            </g>
                        </g>
                        <g transform="translate(13.6, 8)">
                            <g transform="translate(0, 5.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                            <g transform="translate(-1.7, 5.96875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.03125 0,2.03125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.03125 1.7,3.03125 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.21875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.78125 0,2.78125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.78125 1.7,3.78125 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(15.299999999999999, 9)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.53125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.46875 0,1.46875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.46875 1.7,2.46875 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.0625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9375 0,1.9375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9375 1.7,2.9375 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                        </g>
                        <g transform="translate(17, 10)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.53125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.46875 0,1.46875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.46875 1.7,2.46875 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.25)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.75 0,1.75 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.75 1.7,2.75 z"/>
                            </g>
                        </g>
                        <g transform="translate(18.7, 11)">
                            <g transform="translate(0, 4.03125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.96875 0,2.96875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.96875 1.7,3.96875 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                            <g transform="translate(-3.4, 6.78125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.21875 0,2.21875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.21875 1.7,3.21875 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.96875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.03125 0,2.03125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.03125 1.7,3.03125 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                        </g>
                        <g transform="translate(20.4, 12)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 5.6875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.3125 0,2.3125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.3125 1.7,3.3125 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.03125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.96875 0,2.96875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.96875 1.7,3.96875 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(22.099999999999998, 13)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(23.8, 14)">
                            <g transform="translate(0, 5.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.53125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.46875 0,1.46875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.46875 1.7,2.46875 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.25)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.75 0,1.75 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.75 1.7,2.75 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.25)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.75 0,1.75 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.75 1.7,2.75 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(25.5, 15)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 8.46875)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.53125 0,3.53125 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.53125 1.7,4.53125 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.25)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.75 0,1.75 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.75 1.7,2.75 z"/>
                            </g>
                        </g>
                        <g transform="translate(27.2, 16)">
                            <g transform="translate(0, 5.25)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.75 0,1.75 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.75 1.7,2.75 z"/>
                            </g>
                            <g transform="translate(-1.7, 5.96875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.03125 0,2.03125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.03125 1.7,3.03125 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.125 0,2.125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.125 1.7,3.125 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.15625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.84375 0,1.84375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.84375 1.7,2.84375 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(28.9, 17)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.4375)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5625 0,1.5625 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5625 1.7,2.5625 z"/>
                            </g>
                            <g transform="translate(-6.8, 6.0625)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,5.9375 0,4.9375 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,4.9375 1.7,5.9375 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(30.599999999999998, 18)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.4375)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5625 0,1.5625 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5625 1.7,2.5625 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 7.84375)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.15625 0,3.15625 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.15625 1.7,4.15625 z"/>
                            </g>
                            <g transform="translate(-8.5, 8.9375)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.0625 0,3.0625 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.0625 1.7,4.0625 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                        </g>
                        <g transform="translate(32.3, 19)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 1.5625)">
                                <path fill="#216e39" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#216e39" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,7.4375 0,6.4375 z"/>
                                <path fill="#216e39" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,6.4375 1.7,7.4375 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.0625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9375 0,1.9375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9375 1.7,2.9375 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.53125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.46875 0,1.46875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.46875 1.7,2.46875 z"/>
                            </g>
                            <g transform="translate(-6.8, 7.84375)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.15625 0,3.15625 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.15625 1.7,4.15625 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(34, 20)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.0625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.9375 0,1.9375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.9375 1.7,2.9375 z"/>
                            </g>
                            <g transform="translate(-5.1, 7.875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.125 0,2.125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.125 1.7,3.125 z"/>
                            </g>
                            <g transform="translate(-6.8, 8.03125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.96875 0,2.96875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.96875 1.7,3.96875 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.5)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.5 0,2.5 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.5 1.7,3.5 z"/>
                            </g>
                            <g transform="translate(-10.2, 11.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                        </g>
                        <g transform="translate(35.699999999999996, 21)">
                            <g transform="translate(0, 5.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.34375)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.65625 0,1.65625 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.65625 1.7,2.65625 z"/>
                            </g>
                            <g transform="translate(-3.4, 5.9375)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.0625 0,3.0625 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.0625 1.7,4.0625 z"/>
                            </g>
                            <g transform="translate(-5.1, 9)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-6.8, 7.9375)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.0625 0,3.0625 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.0625 1.7,4.0625 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(37.4, 22)">
                            <g transform="translate(0, 4.5)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.5 0,2.5 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.5 1.7,3.5 z"/>
                            </g>
                            <g transform="translate(-1.7, 5.78125)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.21875 0,2.21875 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.21875 1.7,3.21875 z"/>
                            </g>
                            <g transform="translate(-3.4, 5.75)">
                                <path fill="#30a14e" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#30a14e" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,4.25 0,3.25 z"/>
                                <path fill="#30a14e" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,3.25 1.7,4.25 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-6.8, 10)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(39.1, 23)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 6.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.53125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.46875 0,1.46875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.46875 1.7,2.46875 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.375 0,1.375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.375 1.7,2.375 z"/>
                            </g>
                            <g transform="translate(-8.5, 11)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(40.8, 24)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 7.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.4375)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.5625 0,1.5625 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.5625 1.7,2.5625 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.8125)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.1875 0,1.1875 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.1875 1.7,2.1875 z"/>
                            </g>
                            <g transform="translate(-8.5, 9.6875)">
                                <path fill="#40c463" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#40c463" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,3.3125 0,2.3125 z"/>
                                <path fill="#40c463" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,2.3125 1.7,3.3125 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(42.5, 25)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-1.7, 7)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-3.4, 8)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                            <g transform="translate(-5.1, 8.71875)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.28125 0,1.28125 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.28125 1.7,2.28125 z"/>
                            </g>
                            <g transform="translate(-6.8, 9.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                            <g transform="translate(-8.5, 10.90625)">
                                <path fill="#9be9a8" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#9be9a8" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2.09375 0,1.09375 z"/>
                                <path fill="#9be9a8" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1.09375 1.7,2.09375 z"/>
                            </g>
                            <g transform="translate(-10.2, 12)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                        <g transform="translate(44.199999999999996, 26)">
                            <g transform="translate(0, 6)">
                                <path fill="#ebedf0" d="M1.7,2 0,1 1.7,0 3.4,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness1)" d="M0,1 1.7,2 1.7,2 0,1 z"/>
                                <path fill="#ebedf0" filter="url(#brightness2)" d="M1.7,2 3.4,1 3.4,1 1.7,2 z"/>
                            </g>
                        </g>
                    </g>
                </svg>
            </section>
        </div>
        <div xmlns="http://www.w3.org/1999/xhtml" id="metrics-end"></div>
    </foreignObject>
</svg>
<!--
**Kimwonbin0921/Kimwonbin0921** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
