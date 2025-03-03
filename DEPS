# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '99ee11b0106b48f06fb9e2a324ba928b8316cc33',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '2bcbf6b78e5aa5b3670b5f0b0236ca4b56e21e1e',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '54a521dd130ae1b2f38fef79b09515702d135bdd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '12abd77a6b6d779360c25a0d956c08ccfb8f1a3e',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '952f776f6573aafbb62ea717d871cd1d6816c387',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '809941a4ca137df69dc9c6e8eb456bd70309197c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'fb8f5a5d69f4590ff1f5ecacb5e3957b6d11daee',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5f41f2a9bf3589dc5d1791d42ff46f1abe873f2b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '7b234ae04efef41806229ab6689f374398d63cdd',
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
