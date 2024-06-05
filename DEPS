# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4da479aa6afa43e5a2ce4c4148c572a03123faf3',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '27ebab7411bf59f9e9e42a5f6946a03eb9e425b8',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'eb49bb7b1136298b77945c52b4bbbc433f7885de',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '7b5691084a4a54f48bb6ee36219eed06366cace3',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '192d051db3382e213f8bd9d8048fc9eaa78ed6ab',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '377016eea5ebd4f6d6689c1e7a7ca2a2207c3fb4',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0ed7d9d71588f46e972f7fdc9d41ac888b2fa5f6',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '252879e8958afc0c250ed460dbecf43c206fca04',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'cb87374e4ae0eb3272877692ec4d4e777666bca9',
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
