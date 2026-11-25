---
name: web-design-directions
description: Use when creating or redesigning a webpage, exploring its visual style, or looking for alternatives to a generic layout. Propose concise, comparable directions grounded in the page's purpose and content. Describe each direction's palette, typography, imagery, and controls, then let the user choose before implementation. Follow the existing design for local fixes or faithful implementation of an approved design.
---

# Help users choose a web design direction

## Start with the page's purpose

Read the brief and available project materials. Summarize in one sentence who will open the page, in what context, and what they most want to see or do. Identify the real content that could anchor the first screen, such as a detail from a portfolio piece, a match schedule, a work queue, or the opening of an article. Note constraints shared by all options, including the existing brand, required content, primary action, and available assets. If an unclear purpose would change the layout, ask a specific question. For example, ask whether visitors usually arrive to find an older post or to read the latest one.

Choose target devices based on the brief and how people will use the page. For desktop-first work, start at a wide viewport and consider how columns work together, what needs to stay visible at the same time, and how people use the mouse and keyboard. For mobile-first work, start at a narrow viewport and consider reading order and touch interactions. For both, explain how the layout adapts to width. If the user specifies a single device, propose and check the design for that device.

## Offer meaningfully different options

Offer three directions by default, or the number the user requests. Give every option the same primary task while varying at least two of these aspects: the first screen's focus, how content is grouped, the order of later sections, and the path through the page. Borrow from other media when the arrangement serves visitors, as when newspapers lead with the most important story or a program makes performances easy to find by time. Let at least one real detail from the current subject shape the composition. Imagine swapping in a similar project. If changing the name is all it takes, look for a more specific idea in the content.

For a full proposal, read the [design languages reference](references/design-languages.md). Explore different ways to organize the interface before filtering by content and brand. Options might begin with bordered modules, a continuous reading grid, or grouping through shape and surface color. In one sentence per option, explain how its organizing idea shapes the typography, group boundaries, and primary controls. Use color to reinforce those decisions. When the user asks for a local adjustment, wants to compare palettes only, or has already chosen a design language, follow that scope.

Keep proposals to concise text in chat, including when using other frontend design skills. Borrow their methods for thinking through the design. Leave illustrations, wireframes, prototypes, and HTML/CSS previews until the user chooses a direction. If the user explicitly requests a preview, provide it within the requested scope.

When the user only wants to compare palettes, read the [palette reference](references/color-palettes.md) and use the existing layout and controls. Offer two or three short text options, or the number requested. Give each color's name, hex value, and specific placement, along with one tradeoff for the palette. Choose colors that fit the purpose, brand, and actual assets. Then let the user choose. Skip the full proposal format below for this case.

Give each full proposal a plain-language name and two short descriptions. Use the same real content and comparable detail across options, emphasizing what visitors will see on the primary device. If the user wants to explore visual style only, compare styles on the existing layout.

- **Layout and tradeoff.** Describe the first screen's focus, control placement, what comes next, and the benefit or cost to visitors. For task-oriented pages, use one real action per option to show what the layout changes. For example, explain whether staff can check the queue while entering a record and how much list space that requires. For multi-device work, note the main layout changes.
- **Visual style and design elements.** Summarize the visual reference and intended mood in one sentence. Give the background, body text, and accent colors with names and hex values in one line, plus where the accent goes and why. Describe the typeface or letterforms, size, or weight for headings and body text. Explain how imagery will be cropped, toned, framed, or spaced, or how spacing and layout shape a text-only page. Use a real button, navigation item, or selected state to show how controls will look and respond. When motion matters, describe what triggers it, what moves, and when it settles. Flag missing assets and constraints that affect implementation, such as local font fallbacks for offline use.

Read the palette reference as needed for color ideas in full proposals.

Before sharing the options, compare their descriptions. The layouts should differ in content order or visual focus. With the names and colors removed, full proposals should still be distinguishable by type scale, borders or surface grouping, control shapes, and feedback. If recent pages are visible in the current context, check for a repeated opening layout, heading scale, or grouping pattern. When several directions fit equally well, favor one used less recently. If the user wants more randomness, choose from the suitable directions at random. Follow fixed brand standards and vary the parts that have room to change.

## Let the user choose before implementing

Recommend one option in a sentence and tie the reason to the page's purpose. Let the user choose a complete direction or select layout and visual style separately. Share the text proposals and wait for a choice before implementing. If the user has already chosen a direction, provided an approved design, or explicitly delegated the choice, proceed on that basis. When combining options, state which layout and visual elements you are using. If the user asks for more exploration, revisit the layout or style they found unsatisfactory.

Turn the requested changes and elements to keep into specific, verifiable implementation details. For example, place the scenes side by side, reserve orange for the play button, and keep the original border on the selected scene. Record target devices and decisions about typography and imagery. Pass those choices to any frontend implementation or design-system skill you use, and follow the project's brand and components. If a missing asset would require a substitute that changes the experience, let the user decide the tradeoff.

## Verify the design before delivery

1. **Decide what the idea will change before building.** Connect a real piece of content or action to a design decision in one sentence. For example, switching palettes reprints the same film poster in place, so the poster dominates the page and the palette controls sit to the side. Identify the part of the opening view whose focus, proportions, or reading order will change. If the layout must stay, make the decision concrete in the type hierarchy, image treatment, or control shape. For local edits, review within the requested scope.
2. **Inspect the rendered page before delivery.** With a browser or screenshot tool, look at the opening view and the next important section at the target widths. Check the user's choices one by one and try the main interaction. Imagine replacing the title, brand, and palette. Which part of the composition or interaction still shows that the page was designed for this content? Check that similar controls and regions use the chosen type hierarchy, boundaries, and state feedback. Where the layout was fixed, check that the edited elements support the current purpose.
3. **Revise generic results before sharing them.** If the design idea only appears in the proposal, or the page could serve an unrelated project after swapping its text and colors, revise the composition, hierarchy, or control with the biggest impact, then inspect it again. Preserve familiar patterns that are clear and useful, along with the user's constraints. If rendered review is unavailable, explain that limitation.

Inspect the design after implementation. Keep the proposal stage concise and text-only by default.
