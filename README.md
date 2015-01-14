# kurea-contrib-memo

A memo module for Kurea.

## Installation

### npm

To install from npm, run this command in the directory where you installed Kurea:

`npm install kurea-contrib-memo`

### Kurea Package Manager

To install from Kurea at runtime, give Kurea this command:

`!package install kellyirc/kurea-contrib-memo`

## Usage

`!memo [nick(s)] [message]`: to save a memo for someone

 - `nick(s)`: separate users must be separated by `;`'s, aliases for the same user must be separated by `,`'s.

`!memo-list`: to view pending memos

`!memo-cancel [memo #|last]`: to cancel a pending memo
 