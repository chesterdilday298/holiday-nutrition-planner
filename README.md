# Holiday Nutrition Planner - Keystone Endurance

## Deploy to Vercel

### Method 1: Using Vercel CLI (Recommended)

1. Navigate to this folder in your terminal:
   ```bash
   cd path/to/holiday-planner-vercel
   ```

2. Deploy:
   ```bash
   vercel --prod
   ```

3. If you get 404 error, try:
   ```bash
   rm -rf .vercel .next node_modules
   vercel --prod
   ```

### Method 2: GitHub + Vercel

1. Create a GitHub repo
2. Upload these files
3. Import to Vercel from GitHub
4. Deploy

## Troubleshooting

If you see 404 error:
1. Delete the `.vercel` and `.next` folders in this directory
2. Run `vercel --prod` again
3. The build should succeed this time

## Your URL

After deployment: https://your-project.vercel.app
