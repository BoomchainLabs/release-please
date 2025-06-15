# Users

Response Types:

- <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#User">User</a>
- <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserListMissionsResponse">UserListMissionsResponse</a>
- <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserListReferralsResponse">UserListReferralsResponse</a>

Methods:

- <code title="post /users">client.Users.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserService.New">New</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>, body <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserNewParams">UserNewParams</a>) (<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#User">User</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>
- <code title="get /users/{userId}/missions">client.Users.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserService.ListMissions">ListMissions</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>, userID <a href="https://pkg.go.dev/builtin#int64">int64</a>) ([]<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserListMissionsResponse">UserListMissionsResponse</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>
- <code title="get /users/{userId}/referrals">client.Users.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserService.ListReferrals">ListReferrals</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>, userID <a href="https://pkg.go.dev/builtin#int64">int64</a>) ([]<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserListReferralsResponse">UserListReferralsResponse</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>
- <code title="get /users/wallet/{address}">client.Users.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserService.GetByWallet">GetByWallet</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>, address <a href="https://pkg.go.dev/builtin#string">string</a>) (<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#User">User</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>

## Stakes

Response Types:

- <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserStake">UserStake</a>

Methods:

- <code title="post /users/{userId}/stakes">client.Users.Stakes.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserStakeService.New">New</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>, userID <a href="https://pkg.go.dev/builtin#int64">int64</a>, body <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserStakeNewParams">UserStakeNewParams</a>) (<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserStake">UserStake</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>
- <code title="get /users/{userId}/stakes">client.Users.Stakes.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserStakeService.List">List</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>, userID <a href="https://pkg.go.dev/builtin#int64">int64</a>) ([]<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#UserStake">UserStake</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>

# Missions

Response Types:

- <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#Mission">Mission</a>

Methods:

- <code title="get /missions/{id}">client.Missions.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#MissionService.Get">Get</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>, id <a href="https://pkg.go.dev/builtin#int64">int64</a>) (<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#Mission">Mission</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>
- <code title="get /missions">client.Missions.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#MissionService.List">List</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>, query <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#MissionListParams">MissionListParams</a>) ([]<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#Mission">Mission</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>

# Staking

Response Types:

- <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#StakingVault">StakingVault</a>

Methods:

- <code title="get /staking/vaults">client.Staking.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#StakingService.ListVaults">ListVaults</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>) ([]<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#StakingVault">StakingVault</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>

# Stats

Response Types:

- <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#StatGetResponse">StatGetResponse</a>

Methods:

- <code title="get /stats">client.Stats.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#StatService.Get">Get</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>) (<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#StatGetResponse">StatGetResponse</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>

# Token

Response Types:

- <a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#TokenGetInfoResponse">TokenGetInfoResponse</a>

Methods:

- <code title="get /token/info">client.Token.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#TokenService.GetInfo">GetInfo</a>(ctx <a href="https://pkg.go.dev/context">context</a>.<a href="https://pkg.go.dev/context#Context">Context</a>) (<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go">earnapp</a>.<a href="https://pkg.go.dev/github.com/stainless-sdks/earn-app-go#TokenGetInfoResponse">TokenGetInfoResponse</a>, <a href="https://pkg.go.dev/builtin#error">error</a>)</code>
