## Error Type
Console Error

## Error Message
Failed to create file in GitHub repo: The repository or branch might not be fully initialized. Please wait a few moments and try again.


    at useCreateGitDoc.useMutation [as mutationFn] (hooks/useGitDoc.ts:64:15)

## Code Frame
  62 |       if (!response.ok) {
  63 |         const error = await response.json();
> 64 |         throw new Error(error.error || 'Failed to create GitDoc');
     |               ^
  65 |       }
  66 |       
  67 |       return response.json();

Next.js version: 16.0.1 (Turbopack)
## Error Type
Console Error

## Error Message
Failed to create file in GitHub repo: The repository or branch might not be fully initialized. Please wait a few moments and try again.


    at useCreateGitDoc.useMutation [as mutationFn] (hooks/useGitDoc.ts:64:15)

## Code Frame
  62 |       if (!response.ok) {
  63 |         const error = await response.json();
> 64 |         throw new Error(error.error || 'Failed to create GitDoc');
     |               ^
  65 |       }
  66 |       
  67 |       return response.json();

Next.js version: 16.0.1 (Turbopack)
## Error Type
Console Error

## Error Message
Failed to create file in GitHub repo: The repository or branch might not be fully initialized. Please wait a few moments and try again.


    at useCreateGitDoc.useMutation [as mutationFn] (hooks/useGitDoc.ts:64:15)

## Code Frame
  62 |       if (!response.ok) {
  63 |         const error = await response.json();
> 64 |         throw new Error(error.error || 'Failed to create GitDoc');
     |               ^
  65 |       }
  66 |       
  67 |       return response.json();

Next.js version: 16.0.1 (Turbopack)
