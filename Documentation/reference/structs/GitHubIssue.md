**STRUCT**

# `GitHubIssue`

```swift
public struct GitHubIssue: Decodable, Equatable
```

## Properties
### `id`

```swift
public let id: Int
```

> The id number of the issue

### `number`

```swift
public let number: Int
```

> The number of the issue.

### `title`

```swift
public let title: String
```

> The title of the issue.

### `user`

```swift
public let user: GitHubUser
```

> The user who created the issue.

### `state`

```swift
public let state: IssueState
```

> The state for the issue: open, closed, locked.

### `isLocked`

```swift
public let isLocked: Bool
```

> A boolean indicating if the issue has been locked to contributors only.

### `body`

```swift
public let body: String
```

> The markdown body message of the issue.

### `commentCount`

```swift
public let commentCount: Int
```

> The comment number of comments for the issue.

### `assignee`

```swift
public let assignee: GitHubUser?
```

> The user who is assigned to the issue.

### `assignees`

```swift
public let assignees: [GitHubUser]
```

> The users who are assigned to the issue.

### `milestone`

```swift
public let milestone: GitHubMilestone?
```

> The milestone of this issue

### `createdAt`

```swift
public let createdAt: Date
```

> The ISO8601 date string for when the issue was created.

### `updatedAt`

```swift
public let updatedAt: Date
```

> The ISO8601 date string for when the issue was updated.

### `closedAt`

```swift
public let closedAt: Date?
```

> The ISO8601 date string for when the issue was closed.

### `labels`

```swift
public let labels: [GitHubIssueLabel]
```

> The labels associated with this issue.
