# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '90afccfbd49dff0349d86a41762e9de24e1df811',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5ce04fabf196c57af002e1d6fbdb2f1e339a89d1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '942fe4b988359a0750b79f0ae7ed735994d3147d',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5b5a25231a3543559b4f2cb27fe725a08b76b5d0',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f9973cd97e6f3584707e7ef1c425e336f1b92a5b',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e5715c8a3959f2a40a6bc13a3a88a3862843b105',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'd9c353983147b260354764f8d8cc452a8d8c2a36',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '48b2a63b17eb79d612bd276d6e1adeb1f73c03e9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4a33de058dae899fdec1718e9daf81a5eda3bc2d',
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
