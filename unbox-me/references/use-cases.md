# Use cases

Use these cases as patterns for reopening a design space. Diagnose with small contrasts first; do not jump directly to the example breaks.

## 1. Product interface feels generic

**User prompt**

> This analytics dashboard is polished, but it feels like every other SaaS dashboard. Use $unbox-me before changing the visuals.

**Current branch**

The product assumes that users want a persistent overview made of equally available metric cards.

**Possible structural breaks**

- **Delete** the dashboard home and open on the single anomaly that needs attention.
- **Reverse** navigation: start from a decision, then reveal the metrics that support it.
- **Replace** the overview with a time-based briefing that expires after it is read.

The useful move is not a new card style; it is changing what the interface believes the user came to do.

## 2. Software architecture is accumulating patches

**User prompt**

> We keep adding queues, retries, and caches to make this service scale. Use $unbox-me to check whether we are optimizing the wrong architecture.

**Current branch**

The system assumes that every request must synchronously produce a fully assembled result.

**Possible structural breaks**

- **Delete** synchronous completeness and return a stable partial result.
- **Reverse** the data flow so producers publish facts and consumers assemble views.
- **Replace** per-request computation with precomputed, versioned snapshots.

The skill should expose the load-bearing assumption before recommending more infrastructure.

## 3. Brand concept is safe but forgettable

**User prompt**

> The campaign is clear and professional, but no concept survives a day later. Use $unbox-me on the creative direction.

**Current branch**

The campaign assumes that credibility must come from a polished expert voice.

**Possible structural breaks**

- **Delete** the claim of expertise and build the campaign around visible evidence.
- **Reverse** authority by letting customers challenge the brand in public.
- **Replace** the campaign narrative with a recurring ritual people can participate in.

The goal is not to generate twenty more taglines inside the same voice.

## 4. Story premise keeps becoming predictable

**User prompt**

> My story about memory trading keeps turning into a standard conspiracy thriller. Use $unbox-me to reopen it without inventing random plot twists.

**Current branch**

The story assumes that memory trading matters because a hidden institution abuses it.

**Possible structural breaks**

- **Delete** the villain and make the harm emerge from ordinary, consensual use.
- **Reverse** scarcity so forgetting, rather than remembering, becomes the privilege.
- **Replace** the conspiracy frame with a family inheritance conflict.

The breaks change the story engine, not merely the next event.

## 5. Product idea is a familiar category clone

**User prompt**

> We are building another habit tracker with better coaching. Use $unbox-me before we write the roadmap.

**Current branch**

The product assumes that progress comes from recording repeated individual behavior.

**Possible structural breaks**

- **Delete** tracking and only intervene when the surrounding environment changes.
- **Reverse** agency: let a trusted group set and observe commitments.
- **Replace** habit repetition with short, finite experiments that deliberately end.

The result may no longer look like a habit tracker, which is the point of reopening the category boundary.

## 6. Article outline is locally strong but obvious

**User prompt**

> The argument is coherent, but the outline feels inevitable and unsurprising. Use $unbox-me before drafting.

**Current branch**

The article assumes that it should explain the topic by moving from problem to causes to solution.

**Possible structural breaks**

- **Delete** the solution and make the unresolved contradiction the ending.
- **Reverse** the argument by beginning with the strongest counterexample.
- **Replace** exposition with a comparison between two decisions made under the same constraint.

The skill should reopen the reasoning structure before polishing prose.
