# Hosting a Static Website on Amazon S3

This project documents how I hosted a static website using **Amazon S3** as part of the [NextWork](https://nextwork.org) learning program.

## 🛠️ What I Did

- Created a globally unique **S3 bucket** in `ap-south-1` region.
- Uploaded `index.html` and asset files.
- Enabled **static website hosting** via the bucket's **Properties**.
- Configured **Bucket Policy** and **ACL** to allow public access.
- Resolved a `403 Forbidden` error by updating the policy to allow public read.

## 🧠 Key Learnings

- Even after disabling Block Public Access, AWS policies and object permissions matter.
- Static website hosting on S3 is fast, scalable, and easy to configure with proper permissions.

## 📎 Documentation

The full walkthrough with screenshots and notes is available in the PDF:

[📄 Hosted a Website via Amazon S3.pdf](./Hosted%20a%20Website%20via%20Amazon%20S3.pdf)

---

Feel free to fork or reference this if you're learning AWS or hosting static sites!