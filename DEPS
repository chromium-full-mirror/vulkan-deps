# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4a038eafdf9e9f3e0ac2e200127df969f3a51ddb',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '8a466340c0b1477cb5413c3665172fd3b9da2f1f',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '8e82b7cfeca98baae9a01a53511483da7194f854',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'e940239220e38bd5179c26bf43092cc807dfe6fe',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '5ceb9ed481e58e705d0d9b5326537daedd06b97d',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7b6539f24633096c25631bab9fd572bd1ad9b27b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '59dc56aa3023434317a5197d77be51855b5fd2fb',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'ad2ffcba7b2b3f327dcbcb1f825450d49181b46d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '2b23c202d275793f067b1e3821f42eb24edeaa5c',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
