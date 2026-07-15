# Video Production Workflow (SOP) - WealthMind Academy

## Tools Overview

| Tool | Purpose | Cost |
|------|---------|------|
| **NotebookLM Studio Video** | Research, source analysis, script drafting | Free (Google) |
| **AI Studio Google** | AI narration, visual generation, video assembly | Free/Low cost |
| **Canva** | Thumbnail creation | Free tier sufficient |
| **TubeBuddy/VidIQ** | SEO research, tag optimization | $7-$10/month |
| **Google Trends** | Topic validation | Free |
| **YouTube Studio** | Upload, scheduling, analytics | Free |

## Complete Video Production Pipeline

Total time per video: **2-3 hours** (with practice)

---

## Step 1: Topic Research & Validation (20 minutes)

### 1.1 Identify the Topic
- Pull from content calendar or trending topics
- Check Google Trends for search interest
- Verify on YouTube search (type topic, see autocomplete suggestions)

### 1.2 Validate Demand
- Search the topic on YouTube
- Check if top videos have 50K+ views (proves demand)
- Look for gaps: what are they NOT covering?
- Note the top 3 competing videos for reference

### 1.3 Keyword Research
- Use TubeBuddy/VidIQ to find:
  - Primary keyword (high volume, medium competition)
  - 3-5 secondary keywords
  - Long-tail variations
- Document keywords for SEO optimization later

---

## Step 2: Research with NotebookLM (30 minutes)

### 2.1 Set Up NotebookLM Notebook
1. Open [NotebookLM](https://notebooklm.google.com/)
2. Create a new notebook for the video topic
3. Upload sources:
   - 3-5 authoritative articles on the topic
   - Research papers or studies (if available)
   - Competitor video transcripts (use YouTube transcript feature)
   - Book excerpts relevant to the topic

### 2.2 Generate Research Notes
1. Ask NotebookLM to summarize key points from all sources
2. Request: "What are the most important facts and statistics about [topic]?"
3. Ask: "What unique angles are not commonly discussed about [topic]?"
4. Request: "Generate a structured outline for a 10-minute educational video about [topic]"

### 2.3 Use Studio Video Feature
1. In NotebookLM, navigate to Studio > Video
2. Select your sources
3. Generate a video overview/podcast style content
4. Use this as the foundation for your script structure
5. Extract key talking points, statistics, and examples

---

## Step 3: Script Writing with AI Studio (30 minutes)

### 3.1 Set Up AI Studio Google
1. Open [AI Studio Google](https://aistudio.google.com/)
2. Select a text generation model (Gemini Pro or latest)

### 3.2 Generate the Script
Use this prompt template:

```
Write a YouTube video script for a faceless personal finance channel called "WealthMind Academy". 

Topic: [YOUR TOPIC]
Target length: 10 minutes (approximately 1,500 words)
Tone: Authoritative but approachable, data-driven, no hype
Target audience: 22-35 year olds wanting to build wealth

Structure:
1. Hook (first 15 seconds) - shocking stat or question
2. Introduction (30 seconds) - what they'll learn
3. Main content (7-8 minutes) - 3-5 key points with examples
4. Actionable takeaway (1 minute) - specific next steps
5. Call to action (15 seconds) - like, subscribe, watch next video

Include:
- Specific numbers and statistics
- Real-world examples
- Analogies for complex concepts
- Natural transitions between sections
- [KEYWORD] mentioned 3-5 times naturally

Research notes to incorporate:
[PASTE YOUR NOTEBOOKLM NOTES HERE]
```

### 3.3 Edit and Refine the Script
1. Read through the generated script
2. Verify all statistics and claims
3. Add personal touches or unique angles
4. Ensure the hook is compelling (first 15 seconds determine retention)
5. Check that the CTA feels natural
6. Time the script (average speaking rate: 150 words/minute)

### 3.4 Save Script Using Template
- Use the script template at [`/scripts/video-script-template.md`](../scripts/video-script-template.md)
- Save in a organized folder structure by month/week

---

## Step 4: Video Production with AI Studio (45 minutes)

### 4.1 Audio/Narration Generation
1. In AI Studio Google, use text-to-speech capabilities
2. Select a professional, calm male/female voice
3. Generate narration section by section (better quality control)
4. Settings:
   - Speed: 1.0x (normal pace)
   - Tone: Professional, educational
   - Pauses: Add natural pauses between sections

### 4.2 Visual Asset Generation
1. Use AI Studio to generate supporting visuals:
   - Charts and graphs for statistics
   - Conceptual illustrations
   - Text overlays for key points
2. Alternative: Use stock footage from:
   - Pexels (free)
   - Pixabay (free)
   - Storyblocks ($15/month for unlimited)

### 4.3 Video Assembly
1. Combine narration with visuals using AI Studio video features
2. Structure the visual timeline:
   - 0:00-0:15 - Attention-grabbing visual + hook narration
   - 0:15-0:45 - Channel intro motion graphic
   - 0:45-8:00 - Content visuals matching narration
   - 8:00-9:30 - Summary/takeaway visuals
   - 9:30-10:00 - End screen with CTA
3. Add transitions between sections
4. Include text overlays for key numbers/facts

### 4.4 Post-Production Checklist
- [ ] Audio levels consistent throughout
- [ ] No awkward pauses or cuts
- [ ] All statistics displayed on screen when mentioned
- [ ] Intro and outro present
- [ ] End screen elements ready (last 20 seconds)
- [ ] Total length: 8-15 minutes
- [ ] No copyrighted content used

---

## Step 5: Thumbnail Creation (15 minutes)

### 5.1 Design in Canva
1. Open Canva, use 1280x720 template
2. Follow thumbnail guide: [`docs/thumbnail-guide.md`](./thumbnail-guide.md)
3. Key elements:
   - Bold, large text (3-5 words max)
   - Contrasting colors (navy + gold/green)
   - Financial imagery (money, charts, growth arrows)
   - Clean, uncluttered layout

### 5.2 Thumbnail A/B Options
- Create 2 thumbnail versions
- Upload both; use the stronger one
- Test different styles in first month to find what works

---

## Step 6: Upload & Optimization (15 minutes)

### 6.1 Upload to YouTube
1. Open YouTube Studio
2. Upload the video file
3. While processing, fill in metadata:

### 6.2 Title Optimization
- Include primary keyword near the beginning
- Keep under 60 characters
- Use power words: "How to", "Secret", "Actually", numbers
- Follow templates from [`docs/seo-guide.md`](./seo-guide.md)

### 6.3 Description
- First 2 lines: compelling summary (shown in search)
- Include primary and secondary keywords naturally
- Add timestamps for key sections
- Include links (affiliate links, social media, related videos)
- Use description template from SEO guide

### 6.4 Tags
- Primary keyword as first tag
- Include 10-15 relevant tags
- Mix broad and specific tags
- Use TubeBuddy tag suggestions

### 6.5 Additional Settings
- Category: Education or Howto & Style
- Language: English
- End screen: Add subscribe button + next video
- Cards: Link to related videos at relevant timestamps
- Chapters: Add timestamps in description

### 6.6 Schedule
- Best upload times for US audience:
  - Weekdays: 2-4 PM EST
  - Weekends: 9-11 AM EST
- Schedule 24 hours in advance for consistency

---

## Step 7: Post-Upload Tasks (10 minutes)

### 7.1 Community Engagement
- Pin a comment with a question related to the video
- Reply to first 10 comments within 24 hours
- Create a community post teasing the next video

### 7.2 Cross-Promotion
- Create 1-2 YouTube Shorts from video highlights
- Share on social media (Twitter, Reddit finance subs)
- Add to relevant playlists

### 7.3 Performance Tracking
After 48 hours, check:
- Click-through rate (target: >5%)
- Average view duration (target: >50%)
- Impressions count
- Traffic sources

---

## Weekly Batch Production Schedule

For maximum efficiency, batch similar tasks together:

| Day | Task | Videos Covered |
|-----|------|----------------|
| **Saturday** | Research all topics for the week | 3-4 videos |
| **Sunday** | Write all scripts | 3-4 videos |
| **Monday** | Generate narration for all videos | 3-4 videos |
| **Tuesday** | Create visuals and assemble videos | 3-4 videos |
| **Wednesday** | Thumbnails + upload + optimize | 3-4 videos |
| **Thursday** | Schedule uploads, create shorts | 3-4 videos |
| **Friday** | Analytics review, engagement, planning | All videos |

---

## Quality Checklist (Before Every Upload)

- [ ] Hook grabs attention in first 5 seconds
- [ ] Content delivers on the title's promise
- [ ] Statistics are accurate and sourced
- [ ] Audio quality is clear and consistent
- [ ] Visuals are relevant and high-quality
- [ ] No copyrighted music or footage used
- [ ] Title is SEO-optimized and compelling
- [ ] Description includes keywords and timestamps
- [ ] Thumbnail is eye-catching and readable
- [ ] End screen and cards are configured
- [ ] Video is scheduled for optimal time

---

*Catatan: Workflow ini bisa diselesaikan dalam 2-3 jam per video setelah terbiasa. Dengan batch production, Anda bisa membuat 3-4 video dalam satu hari kerja penuh.*
