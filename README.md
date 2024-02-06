### NearBadger and Frensly projects

NearBadger is the platform that allows users to prove that they own a profile in a given web3 social platform (such as Lens Protocol, Farcaster, Mirror...), by providing an intuitive and simple User Interface, where users have to sign a message with their EVM-based wallet and save the signature to their Near account in order to prove other users that they own a given handle

Frensly is one of the platforms that leverages NearBadger tools to create a unique social platform on Near Protocol where users owning a Lens Profile can get to know and interact with other users owning a verified Lens Profile on Near Protocol in a fancy and cozy environment

## How to run the project
1. Install the dependencies of the project by running the following command
```
npm install
```
2. Run the development environment
```
npm run dev
```
3. Navigate ìn your browser to `http://127.0.0.1:8080/` or `http://127.0.0.1:4040/` depending if your port `8080` is already taken by another process
4. The path to the homepage of each platforms:
- NearBadger: /mattb.near/widget/NearBadger.Pages.Main
- Frensly: /mattb.near/widget/Frensly.Pages.Index

> [!IMPORTANT]
> Frensly leverages new and experimental dev tooling such as `RoutesManager` and `useSharedContext`

## Demo Video
[Click here to see the video on Loom](https://www.loom.com/share/e50ef6196a5040f5b431d90e9c05d646?sid=4e906135-d582-487b-aa2a-36f83b44cd57)

## Bounties
- General Prize
- Abstraction on bOS

