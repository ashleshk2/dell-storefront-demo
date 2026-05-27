Warning: True color (24-bit) support not detected. Using a terminal with true color enabled will result in a better visual experience.
Ripgrep is not available. Falling back to GrepTool.
Attempt 1 failed: You exceeded your current quota, please check your plan and billing details. For more information on this error, head to: https://ai.google.dev/gemini-api/docs/rate-limits. To monitor your current usage, head to: https://ai.dev/rate-limit. 
* Quota exceeded for metric: generativelanguage.googleapis.com/generate_content_free_tier_requests, limit: 5, model: gemini-3-flash
Please retry in 25.338215412s.
Suggested retry after 25s.. Retrying after 29364ms...
Attempt 2 failed with status 503. Retrying with backoff... _ApiError: {"error":{"message":"{\n  \"error\": {\n    \"code\": 503,\n    \"message\": \"This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.\",\n    \"status\": \"UNAVAILABLE\"\n  }\n}\n","code":503,"status":"Service Unavailable"}}
    at throwErrorIfNotOK (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:36185:24)
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:35948:7
    at async Models.generateContentStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:37044:16)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:273597:19
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:250407:23
    at async retryWithBackoff (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270684:23)
    at async GeminiChat.makeApiCallAndProcessStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293631:28)
    at async GeminiChat.streamWithRetries (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293450:29)
    at async Turn.run (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:294024:24) {
  status: 503
}
Attempt 1 failed with status 503. Retrying with backoff... _ApiError: {"error":{"message":"{\n  \"error\": {\n    \"code\": 503,\n    \"message\": \"This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.\",\n    \"status\": \"UNAVAILABLE\"\n  }\n}\n","code":503,"status":"Service Unavailable"}}
    at throwErrorIfNotOK (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:36185:24)
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:35948:7
    at async Models.generateContentStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:37044:16)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:273597:19
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:250407:23
    at async retryWithBackoff (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270684:23)
    at async GeminiChat.makeApiCallAndProcessStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293631:28)
    at async GeminiChat.streamWithRetries (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293450:29)
    at async Turn.run (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:294024:24) {
  status: 503
}
Attempt 2 failed with status 503. Retrying with backoff... _ApiError: {"error":{"message":"{\n  \"error\": {\n    \"code\": 503,\n    \"message\": \"This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.\",\n    \"status\": \"UNAVAILABLE\"\n  }\n}\n","code":503,"status":"Service Unavailable"}}
    at throwErrorIfNotOK (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:36185:24)
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:35948:7
    at async Models.generateContentStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:37044:16)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:273597:19
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:250407:23
    at async retryWithBackoff (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270684:23)
    at async GeminiChat.makeApiCallAndProcessStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293631:28)
    at async GeminiChat.streamWithRetries (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293450:29)
    at async Turn.run (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:294024:24) {
  status: 503
}
Attempt 3 failed: You exceeded your current quota, please check your plan and billing details. For more information on this error, head to: https://ai.google.dev/gemini-api/docs/rate-limits. To monitor your current usage, head to: https://ai.dev/rate-limit. 
* Quota exceeded for metric: generativelanguage.googleapis.com/generate_content_free_tier_requests, limit: 5, model: gemini-3-flash
Please retry in 12.220604999s.
Suggested retry after 12s.. Retrying after 22210ms...
Error when talking to Gemini API Full report available at: C:\Users\ashle\AppData\Local\Temp\gemini-client-error-Turn.run-sendMessageStream-2026-05-27T17-12-06-122Z.json TerminalQuotaError: You have exhausted your daily quota on this model.
    at classifyGoogleError (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270038:16)
    at retryWithBackoff (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270707:31)
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async GeminiChat.makeApiCallAndProcessStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293631:28)
    at async GeminiChat.streamWithRetries (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293450:29)
    at async Turn.run (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:294024:24)
    at async GeminiClient.processTurn (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:306709:22)
    at async GeminiClient.sendMessageStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:306797:14)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/gemini-QSTQ2DBG.js:10859:26
    at async main (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/gemini-QSTQ2DBG.js:16137:5) {
  cause: {
    code: 429,
    message: 'You exceeded your current quota, please check your plan and billing details. For more information on this error, head to: https://ai.google.dev/gemini-api/docs/rate-limits. To monitor your current usage, head to: https://ai.dev/rate-limit. \n' +
      '* Quota exceeded for metric: generativelanguage.googleapis.com/generate_content_free_tier_requests, limit: 20, model: gemini-3-flash\n' +
      'Please retry in 53.592037712s.',
    details: [ [Object], [Object], [Object] ]
  },
  retryDelayMs: undefined,
  reason: undefined
}
An unexpected critical error occurred:[object Object]
