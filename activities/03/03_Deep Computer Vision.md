# Computer Vision on Your Own Photos

| | |
|---|---|
| **Notebook** | [`CSC173_Deep Computer_Vision_Demo.ipynb`](https://github.com/jjmmontemayor/csc173-1s-2026/blob/main/activities/03/CSC173_Lecture03_Deep_Computer_Vision_Demo.ipynb) (in this folder) · [Open in Colab](https://colab.research.google.com/github/jjmmontemayor/csc173-1s-2026/blob/main/activities/03/CSC173_Lecture03_Deep_Computer_Vision_Demo.ipynb) |
| **Mode** | Individual |
| **Deadline** | **October 30, 2026, 11:59 PM (Philippine Time, UTC+8)** |
| **Submit on Moodle** | Repository URL and commit hash |
| **You need** | 3 to 5 photos you took yourself, and at least 20 photos for each of two categories |

This activity puts the Lecture 03 topics into practice on **photos you take yourself**:

- images as numbers;
- convolution, stride and padding;
- ReLU and pooling;
- a pretrained CNN (MobileNetV2) and what it looks at;
- Vision Transformer patches;
- transfer learning.


## Before you start: take your photos

| For | What | How many |
|---|---|---|
| Parts 1 to 6 | Photos you took yourself. Include **one with strong straight edges** (a building, a window, a page of text, stairs) and **one of an everyday object** (a mug, a keyboard, a shoe, a bicycle, a pet). | 3 to 5 |
| Part 7 | Two categories of objects you can photograph many times. Examples: *mango vs. banana*, *my pen vs. my pencil*, *jeepney vs. tricycle*. Vary the background, angle and lighting. | at least 20 per category |

- Use JPG or PNG. On an iPhone, set *Settings → Camera → Formats → Most Compatible*, or export the photos as JPG.
- For Part 7, put the photos in one folder per category and zip the parent folder as `my_dataset.zip`:

  ```text
  my_dataset/
      mango/    IMG_001.jpg  IMG_002.jpg ...
      banana/   IMG_101.jpg  IMG_102.jpg ...
  ```

- Do not photograph other people without their permission. Do not include anything private, such as IDs, documents or screens with personal information.

## What to do

1. **Open the notebook in Google Colab.** In Colab, choose *File → Open notebook → GitHub*, paste this repository's URL, and select `CSC173_Lecture03_Deep_Computer_Vision_Demo.ipynb`. Then choose *File → Save a copy in Drive* so you can edit it. Jupyter also works: run `pip install tensorflow pillow matplotlib`, put your photos in a `my_images/` folder and your dataset in a `my_dataset/` folder next to the notebook.
2. **Upload your photos in Part 0** and set `MY_PICK` to your photo with strong edges. If no photos are found, the notebook uses a sample photo, and in Part 7 a flower dataset. Those are only so the code runs; your submission must use **your own** photos.
3. **Fill in every cell marked `# TODO`.** The check lines (`Check: True`, `matches tf.nn.conv2d: True`) tell you whether your code is right. The notebook has seven parts:
   1. **Images are numbers:** shape, grayscale, flattening and the cost of a Dense layer.
   2. **Convolution by hand:** the output-size formula, your own `conv2d`, edge and blur kernels, **a kernel you design**, and a filter over three color channels.
   3. **ReLU and pooling:** max, average and sum pooling, and what pooling does when the photo shifts.
   4. **A pretrained CNN:** MobileNetV2 classifies your photos, then you try to fool it.
   5. **Inside the network:** learned filters, feature maps at four depths, and Grad-CAM.
   6. **ViT patches:** cut your photo into 16×16 tokens.
   7. **Transfer learning:** train a classifier on your two categories, compare it with a CNN trained from scratch, inspect its mistakes, and test it on one brand-new photo.
4. **Answer the 8 ✍️ questions and the final reflection** in the *Your answer:* cell below each one. Many answers depend on your photos, so describe what **you** see in **your** outputs.
5. **Run everything from top to bottom** one last time (*Runtime → Restart and run all*) so the outputs match the code.

## What to put in your repository

Use your own CSC173 repository:

```text
student-csc173-repository/
└── activities/
    └── 03/
        ├── CSC173_Lecture03_Deep_Computer_Vision_Demo.ipynb   # your copy, run, with outputs saved
        └── notes.md                                         # your photos, your dataset, and outside help
```

- Save the notebook **with its outputs**. In Colab, choose *File → Download → Download .ipynb*, then upload it to your repository. The outputs show your photos, so there is no need to upload the photos separately.
- If GitHub cannot display your notebook because it is too large, open the notebook in Colab, choose *Edit → Clear all outputs*, run *Restart and run all* once more, and download it again. Large photos are shrunk inside the notebook, so this is rare.

### `notes.md` template

```markdown
# Lecture 03 Activity: Notes
Name: · Student ID:

## My photos (Parts 0 to 6)
How many photos, and what each shows (one line each):

## My dataset (Part 7)
Categories: … vs. …
Photos per category: … and …
How I took them (places, backgrounds, lighting, angles):
Final validation accuracy: transfer … · from scratch …

## My kernel (Part 2c)
The numbers, and what it detects:

## AI and outside help
List any AI tools, websites or classmates you used, and for what. Write "None" if none.
```

## How to submit

1. Commit and push `activities/03/` to your repository.
2. Copy the **commit hash** of that push. On GitHub, open your repository, click the commit count (the clock icon), and copy the full hash of your latest commit. From a terminal, run `git log -1 --format=%H`.
3. On MOLE, submit:
   - your repository URL, and
   - the commit hash.

Only the version at that commit is checked. Pushing again after the deadline does not change your submission.

## Rules

- **Individual work.** You may discuss ideas, but your photos, dataset, runs, numbers and explanations must be your own. Two students may not submit the same photos or dataset.
- **Disclose AI and outside help** in `notes.md`. You must be able to explain everything you submit, including why your kernel works and why your model made its mistakes.
- Submissions that still show the sample photo or the flower dataset are incomplete.
- Your repository is public: no photos of other people without their permission, and no grades, passwords, API keys or other credentials.


