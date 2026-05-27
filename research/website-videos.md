Warning: True color (24-bit) support not detected. Using a terminal with true color enabled will result in a better visual experience.
Ripgrep is not available. Falling back to GrepTool.
Attempt 1 failed. Retrying with backoff... Error: exception TypeError: fetch failed sending request
    at file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:36023:13
    at async Models.generateContentStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:37044:16)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:273597:19
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:250407:23
    at async retryWithBackoff (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270684:23)
    at async GeminiChat.makeApiCallAndProcessStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293631:28)
    at async GeminiChat.streamWithRetries (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293450:29)
    at async Turn.run (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:294024:24)
    at async GeminiClient.processTurn (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:306709:22)
    at async GeminiClient.sendMessageStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:306797:14)
Attempt 2 failed. Retrying with backoff... Error: exception TypeError: fetch failed sending request
    at file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:36023:13
    at async Models.generateContentStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-JEW7ZIWE.js:37044:16)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:273597:19
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:250407:23
    at async retryWithBackoff (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270684:23)
    at async GeminiChat.makeApiCallAndProcessStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293631:28)
    at async GeminiChat.streamWithRetries (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293450:29)
    at async Turn.run (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:294024:24)
    at async GeminiClient.processTurn (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:306709:22)
    at async GeminiClient.sendMessageStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:306797:14)
Attempt 1 failed: You exceeded your current quota, please check your plan and billing details. For more information on this error, head to: https://ai.google.dev/gemini-api/docs/rate-limits. To monitor your current usage, head to: https://ai.dev/rate-limit. 
* Quota exceeded for metric: generativelanguage.googleapis.com/generate_content_free_tier_requests, limit: 5, model: gemini-3-flash
Please retry in 19.89633774s.
Suggested retry after 19s.. Retrying after 21950ms...
Attempt 2 failed: You exceeded your current quota, please check your plan and billing details. For more information on this error, head to: https://ai.google.dev/gemini-api/docs/rate-limits. To monitor your current usage, head to: https://ai.dev/rate-limit. 
* Quota exceeded for metric: generativelanguage.googleapis.com/generate_content_free_tier_requests, limit: 5, model: gemini-3-flash
Please retry in 57.637196847s.
Suggested retry after 57s.. Retrying after 65901ms...
Subagent 'codebase_investigator' failed: TerminalQuotaError: You have exhausted your daily quota on this model.
    at classifyGoogleError (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270038:16)
    at retryWithBackoff (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:270707:31)
    at process.processTicksAndRejections (node:internal/process/task_queues:104:5)
    at async GeminiChat.makeApiCallAndProcessStream (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293631:28)
    at async GeminiChat.streamWithRetries (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:293450:29)
    at async _LocalAgentExecutor.callModel (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:309252:22)
    at async _LocalAgentExecutor.executeTurn (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:308835:43)
    at async _LocalAgentExecutor.runInternal (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:309045:30)
    at async LocalSubagentInvocation.execute (file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:309875:22)
    at async file:///C:/Users/ashle/AppData/Roaming/npm/node_modules/@google/gemini-cli/bundle/chunk-7VVHSNDQ.js:312161:23 {
  cause: {
    code: 429,
    message: 'You exceeded your current quota, please check your plan and billing details. For more information on this error, head to: https://ai.google.dev/gemini-api/docs/rate-limits. To monitor your current usage, head to: https://ai.dev/rate-limit. \n' +
      '* Quota exceeded for metric: generativelanguage.googleapis.com/generate_content_free_tier_requests, limit: 20, model: gemini-3-flash\n' +
      'Please retry in 51.319600479s.',
    details: [ [Object], [Object], [Object] ]
  },
  retryDelayMs: undefined,
  reason: undefined
}
Error when talking to Gemini API Full report available at: C:\Users\ashle\AppData\Local\Temp\gemini-client-error-Turn.run-sendMessageStream-2026-05-27T17-12-08-719Z.json TerminalQuotaError: You have exhausted your daily quota on this model.
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
      'Please retry in 50.992712304s.',
    details: [ [Object], [Object], [Object] ]
  },
  retryDelayMs: undefined,
  reason: undefined
}
An unexpected critical error occurred:[object Object]
