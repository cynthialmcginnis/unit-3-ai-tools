# Unit 3: AI Tools and Implementation

An interactive lecture and a hands-on team activity about putting AI to work: why most AI projects fail, what the successful ones do differently, and how to test a cloud AI service on your own examples before you trust it.

## What's here

| File | What it is |
|---|---|
| `index.html` | The start page. It links to the lecture and the activity. |
| `lecture.html` | The lecture, as a page-turning book. Students follow along on their own laptops, answer checks, and type notes. Everything they type saves in their own browser and prints with the lecture. |
| `shelf-check.html` | **Shelf Check**, a team activity in Amazon Rekognition, a cloud AI service from Amazon Web Services (AWS) that reads text in images. Each student writes an answer key, tests 5 practice images, and records what Rekognition read. The team pools 15 results and sees its hit rate, a plausible range for the real hit rate, and its most confident mistake. |
| `shelf-check-images.zip` | The 15 practice images as separate JPEG files. The same images are built into `shelf-check.html`. |

## The lecture

Six sections:

1. Why AI projects fail
2. What successful projects do differently
3. What does a wrong prediction cost?
4. Implementation is a cycle
5. The five parts of a working AI system
6. Cloud AI: test, compare, or build

Controls in the top bar:

- **Pick a student** chooses a name at random. No name repeats until everyone has been picked.
- **Class list** sets the names. They save only in your own browser and are never stored in this repository.
- **Print** prints the whole lecture with the answers typed on that laptop.

Use the arrow keys or the ◀ ▶ buttons to turn pages.

This is the student copy. The instructor's talking points are not included.

## Shelf Check

Students need access to an AWS Academy Learner Lab. They use Rekognition's **Text in image** demo in the AWS console. No programming and no API key are needed.

Every practice image was drawn with code to look like a phone photo. None came from the internet or from a GenAI image tool. Nine of the 15 are built to be hard for a text reader but still readable by a person: handwriting, a steep angle, glare, a dot-printed label, a curved can, low light, a busy background, and small print.

## Hosting

1. Upload all five files to the main branch of this repository.
2. Go to **Settings > Pages**. Under **Branch**, choose **main** and **/ (root)**, then select **Save**.
3. After a minute or two, the site is live at `https://<your-username>.github.io/<repository-name>/`.

The pages work offline, except for the web fonts and the 3D views in the lecture.
